# Blog
My personal blog

## Requirements
In able to compile and run project, make sure `go 1.18` or later is installed.
You might need to install `hugo` as well, check out their documentation.

Clone repository by `git clone` to your local computer:
```shell script
$ git clone git@github.com:khoarx/blog.git
$ cd blog
```

## Build and test
Start Hugo's development server to view site
```shell script
$ hugo server
```
for draft content
```shell script
$ hugo server -D
```

Add new page to site
```shell script
$ hugo new [folder]/[page-name].md
```
For example:
```shell script
$ hugo new posts/fluffy-otter.md
```

To publish the site, simply execute `hugo` and the entire static site in the _public/_ directory.

## References
[HUGO](https://gohugo.io/) \
[The Markdown Guide](https://www.markdownguide.org/)

