[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/tubone24/resume)

# tubone resume

[![Actions Status](https://github.com/tubone24/resume/workflows/Build%20and%20Deploy/badge.svg)](https://github.com/tubone24/resume/actions?query=workflow%3A%22Build+and+Deploy%22)

tubone's resume using by [Json Resume](https://jsonresume.org/)

## Json Resume API

Created by [API with GitHub](https://apiwithgithub.com/editor/tubone24/resume-json-data)

[API](https://raw.githubusercontent.com/tubone24/resume-json-data/master/resume.json)

## How Deploy

First, install resume-cli

```
npm install -g resume-cli
```

And, install dependant packages with npm

```
npm install
```

Next, preview local [http://localhost:4000](http://localhost:4000)

```
npm run develop
```

Build HTML

```
npm run build-html
```

Build PDF

```
npm run build-pdf
```

## HTML FORMAT

Hosting by Github-pages.

[https://tubone24.github.io/resume/](https://tubone24.github.io/resume/)

## PDF FORMAT

Hosting by Github-pages.

[https://tubone24.github.io/resume/PDF.pdf](https://tubone24.github.io/resume/PDF.pdf)

## CI/CD

The repository uses `GitHub Actions` to commit the built files to the gh-pages branch.

With GitHub Pages, all you have to do is commit the `resume.json` file and you'll get a It will be released.
