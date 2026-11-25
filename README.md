# CU5 student MkDocs

Static student materials for CU5, built for learning-portal iframe embeds.

## Unit URLs (after Netlify deploy)

- `/DS_1.1/` — Python Fundamentals
- `/DS_1.2/` — Data Preparation & Statistical Modelling
- `/DS_1.3/` — Machine Learning and Deep Learning

## Embed example

```html
<iframe
  src="https://YOUR-SITE.netlify.app/DS_1.1/"
  title="DS_1.1 student materials"
  style="width:100%;min-height:80vh;border:0;"
></iframe>
```

## Rebuild

Source lives in the local CU5 `docs-site` project. Rebuild there, then replace the unit folders in this repo and push.
