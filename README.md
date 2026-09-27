Templates modified based on [gregorygundersen.com/blog](http://gregorygundersen.com/blog/). For details, see [this post](http://gregorygundersen.com/blog/2020/06/21/blog-theme).

## Local preview

This site uses Jekyll layouts, so serving the source directory directly with `live-server` does not render pages such as `/research/` and `/talks/`. Preview the site with Jekyll instead:

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://127.0.0.1:4000/>. Alternatively, build first with `bundle exec jekyll build` and run `live-server _site`.
