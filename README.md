# QUAAA 2027

Website of the QUAAA workshop (April 10, 2027, Copenhagen, co-located with ETAPS 2027),
built with Jekyll and published via GitHub Pages
(*Settings → Pages → Deploy from a branch*, `main`, `/ (root)`).

## Editing

| What                          | Where                     |
|-------------------------------|---------------------------|
| About / call for submissions  | `index.md` (Markdown)     |
| Title, date, submission link  | `_config.yml`             |
| Important dates               | `_data/dates.yml`         |
| Organizers                    | `_data/organizers.yml`    |
| Program committee             | `_data/pc.yml`            |
| Program                       | `_data/program.yml`       |
| Accepted papers               | `_data/papers.yml` (PDFs go in `papers/`) |
| Style                         | `assets/css/style.css`    |

The program and paper sections appear automatically once their lists are non-empty;
each data file contains a commented example entry.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000/quaaa/>.
