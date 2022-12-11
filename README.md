# Blog
My personal blog

## Requirements
In able to compile and run project, make sure `zola` is installed, check out their documentation.

Clone repository by `git clone` to your local computer:
```shell script
$ git clone git@github.com:khoarx/blog.git
$ cd blog
```

## Build and test
Start Zola's development server to view site
```shell script
$ zola serve
```

To use another theme for your site, add theme repo to _themes_ folder
```shell script
git submodule add [theme_repo_url] themes/[theme_name]
```
then modify setting in `config.toml`

## References
[Zola](https://www.getzola.org/) \
[The Markdown Guide](https://www.markdownguide.org/)

