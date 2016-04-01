# blog
This is the content repository supplying blog to https://bcdevexchange.org, powered by [Jekyll](http://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/). The repo has 2 branches: `gh-pages` (default) and `master`. https://bcdevexchange.org uses `gh-pages` branch and https://uat.bcdevexchange.org uses `master` branch. The UAT environment, and therefore `master` branch, is for previewing/proof-reading a blog prior to publishing to prod. See [Jekyll Docs](https://jekyllrb.com/docs/posts/) about composing a blog posting. It's easier to start by duplicating an existing post. Only posts bearing category `BCDev` in the [Front Matter](https://jekyllrb.com/docs/frontmatter/) section are displayed on https://[uat.]bcdevexchange.org. In essence, the workflow to post a blog is:

1. Duplicate an existing blog in `_posts` folder of `master` branch and modify it.
2. Preview the blog on https://uat.bcdevexchange.org. There is a latency of about 5min for changes to appear on site.
3. Publish the blog to https://bcdevexchange.org by copying the file from `master` branch to `_posts` folder of `gh-pages` branch. 
4. To unpublish, You can either delete the file or take out `BCDev` from the category.
