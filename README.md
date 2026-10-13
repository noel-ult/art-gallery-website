# Art gallery website

A static HTML gallery with five artwork detail pages and demonstration login and signup forms.

## Preview

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open http://localhost:8000. A browser and Python are sufficient for this preview; opening `index.html` directly also works for local navigation. Keep image files alongside the HTML when copying the site.

## Pages

| File | Content |
| --- | --- |
| `index.html` | Gallery home and artwork navigation |
| `art1.html` | The Starry Night |
| `art2.html` | The Persistence of Memory |
| `art3.html` | Mona Lisa |
| `art4.html` | Girl with a Pearl Earring |
| `art5.html` | The Scream |
| `login.html` | Login form layout |
| `signup.html` | Signup form layout |

## Current scope

Login and signup are HTML demonstrations: no JavaScript handlers, authentication service, or database is present. External stylesheet resources require network access. Edit content and styling in the HTML pages, then check all artwork links, image paths, forms, and narrow-screen layouts. There is no build command or automated test suite. Deploy the directory as static files.

## More documentation

- [Source, command, and configuration reference](docs/REFERENCE.md)
- [Contributing](CONTRIBUTING.md)
