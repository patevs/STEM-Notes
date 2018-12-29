# STEM-Notes

Netlify deployment: https://stem-notes.netlify.com/

Build using the [Hugo](https://gohugo.io/) framework and static site generator with theme cloned from: [achary/engimo](https://github.com/achary/engimo)

## Setup Instructions

```bash
git clone https://github.com/patevs/STEM-Notes.git
cd STEM-Notes
# run development server
hugo server
# run production build of site
hugo
# trigger deployment with remote push or manually
# requires netlify-cli installed globally
netlify deploy
```

## Resources

* [Hugo](https://gohugo.io/)
  * [`CLI`](https://www.npmjs.com/package/hugo-cli)
  * [`Commands`](https://gohugo.io/commands/)
  * [`Documentation`](https://gohugo.io/documentation/)
  * [`Themes`](https://themes.gohugo.io/)
* [Netlify](https://app.netlify.com/account/sites)
  * [`CLI`](https://www.npmjs.com/package/netlify-cli)
  * [`CMS`](https://www.netlifycms.org/docs/add-to-your-site/)
  * [`Commands`](https://www.netlify.com/docs/cli/)
  * [`Documentation`](https://www.netlify.com/docs/)

----

`2018 | Patrick Evans`

----
