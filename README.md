# Dr. Axiu Mao's homepage

Source of <https://max-1234-hub.github.io/>, the homepage of Dr. Axiu Mao at Hangzhou Dianzi University.
The site is built with [Jekyll](https://jekyllrb.com) on top of the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template (MIT licence, see `LICENSE`).

## Publishing

The site is built and deployed by GitHub Actions (`.github/workflows/jekyll.yml`) on every push to `main`.

One-time setup in the GitHub repository: **Settings → Pages → Build and deployment → Source: GitHub Actions**.

## Where to edit

| To change… | Edit… |
|:--|:--|
| Site title, sidebar profile, links | `_config.yml` |
| Menu bar | `_data/navigation.yml` |
| Home page text | `_pages/about.md`; awards in `_data/awards.yml` |
| News on the home page | `_data/news.yml` (add new items at the top) |
| Research topics, figures, projects, patents | `_data/research.yml`, figures in `images/research/` |
| Publications (used by the Publications and Research pages) | `_data/publications.yml`, thumbnails in `images/pubs/` |
| Team members | `_data/team.yml`, photos in `images/team/` |
| Teaching page | `_pages/teaching.md`; competition guidance in `_data/competitions.yml` |
| Activity page (service, oral reports, media) | `_pages/activity.md` |
| Styles of the lab-specific pages | `_sass/layout/_lab.scss` |

### Adding a paper

Add an entry to `_data/publications.yml`. Its `topics` field decides under which research direction it
appears on the Research page (`wearable`, `vision`, `multimodal`, `others`).

### Adding a team member

Add an entry under the right group in `_data/team.yml`. With `photo: "name.jpg"` the portrait is read from
`images/team/`; without it a badge with the member's initials is shown.

## Local preview (optional)

With Ruby installed: `bundle install`, then `bundle exec jekyll serve -l -H localhost` and open <http://localhost:4000>.
Alternatively use the provided Docker setup: `docker compose up`.
