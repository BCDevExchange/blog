# blog
This is the content repository supplying blog to https://bcdevexchange.org, powered by [Jekyll](http://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/). Drafts and post-dated blogs can be previewed in [UAT](https://uat.bcdevexchange.org/blog) environment. See [Jekyll Docs](https://jekyllrb.com/docs/posts/) about composing a blog posting. It's easier to start by duplicating an existing post. Only posts bearing category `BCDev` in the [Front Matter](https://jekyllrb.com/docs/frontmatter/) section are displayed on https://[uat.]bcdevexchange.org. In essence, the workflow to post a blog is:

1. Duplicate an existing blog to `_drafts` folder and modify it.
2. Preview the blog on https://uat.bcdevexchange.org.
3. Publish the blog to https://bcdevexchange.org by moving the file from `_drafts` folder to `_posts` folder.
4. To unpublish, You can do one of following:
    1. take out `BCDev` from the category;
    2. set variable [`published`](https://jekyllrb.com/docs/frontmatter/#predefined-global-variables) to true in Front Matter;
    3. move the file from `_posts` to `_drafts` folder;
    4. delete the file; 
