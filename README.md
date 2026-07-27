# USC SAIL 25th Anniversary Workshop — Website

Source for the public website of the **25th Anniversary Workshop of the Signal
Analysis and Interpretation Laboratory (SAIL)** at the University of Southern
California.

**Live site:** https://huangchengchou.com/sail25-workshop-page/

The workshop brought together SAIL alumni and current members to review
twenty-five years of research in human-centered signal processing and machine
learning, spanning speech, language, behavioral signal processing, and health.

## What is in here

| Path | Contents |
|---|---|
| `index.html` | Single-page site: programme, speakers, venue, registration |
| `style.css` | Layout and theme |
| `script.js` | Schedule filtering and navigation behaviour |
| `images/` | Speaker portraits and workshop photography |
| `posters/` | Poster session material |

## Running it locally

The site is static with no build step or dependencies:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080/`.

## Credits

Built and maintained by [Huang-Cheng Chou](https://github.com/ag027592) and
Naveen Kumar for USC SAIL. Site content belongs to the laboratory and its
contributors.
