# 420 Smokers Jamstack

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

  <br />

![](static/screens/screenshot.png) <br />

  <br />

## Description

This is the new home of 420smokers.us

## Features:

* Easy editable content in prismic.io CMS
* **CSS** with `styled-jsx` and `PostCSS`
* **SEO** (sitemap generation, robot.txt, meta and OpenGraph Tags)
* **Social** sharing (Twitter, Facebook, Google, LinkedIn)
* **Comments** (Facebook)
* **Images** lazy loading and `webp` support (gatsby-image)
* **Guide List** (prismic gatsby)
* **Contact** form (Netlify form handling)
* Form elements and validation with `ant-design`
* **RSS** feed
* 100% **PWA** (manifest.webmanifest, offline support, favicons)
* Google **Analytics**
* App **favicons** generator (node script)
* Easy customizable base **styles** via `theme` object generated from `yaml` file (fonts, colors, sizes)
* React **v.16.3** (gatsby-plugin-react-next)
* **Components** lazy loading (social sharing)
* **ESLint** (google config)
* **Prettier** code styling
* Webpack `BundleAnalyzerPlugin`

## Prerequisites

If you do not have Gatsby Cli installed yet, do it first.

```text
npm install --global gatsby-cli
```

More information on [GatsbyJS.org](https://www.gatsbyjs.org/tutorial/part-one)

## Getting started

Install the app by using Gatsby Cli `gatsby new` command.

```text
gatsby new [NEW_SITE_DIRECTORY_FOR_YOUR_BLOG] https://github.com/anxiousstoner/gatsby-420.git
```

Go into the newly created directory and run

```text
gatsby develop
```

to hot-serve your website on http://localhost:8000 or

```text
gatsby build
```

to create static site ready to host (/public).

##### External services

The starter uses external services for some functions: comments, searching, analytics. To use them you have to secure some access data. All services are free to use or have generous free tiers big enough for a personal blog.

Create an `.env` file like below in the root folder. Change `...` placeholders with real data.

```text
GOOGLE_ANALYTICS_ID=...
FB_APP_ID=...
PRISMIC_REPO_NAME=...
PRISMIC_ACCESS_TOKEN=...
```

### Instructions & tutorials

Coming Soon... (For now you need our .env or match the data exactly)

## Based on the theme by:

* Greg Lobinski [@greglobinski](https://github.com/greglobinski)

See also the list of [contributors](https://github.com/greglobinski/gatsby-starter-personal-blog/graphs/contributors) who participated in this project.

## Contributing

* Fork the repo
* Create your feature branch (git checkout -b feature/fooBar)
* Commit your changes (git commit -am 'Add some fooBar')
* Push to the branch (git push origin feature/fooBar)
* Create a new Pull Request

## Licence

MIT License

Copyright (c) 2017 gatsbyjs <br />Copyright (c) 2018 greg lobinski

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
