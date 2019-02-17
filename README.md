# mysite

[quickstart](https://gohugo.io/getting-started/quick-start/)

[theme](https://github.com/danielkvist/hugo-terrassa-theme) by danielkvist

+ Markdown
https://gohugo.io/content-management/formats/

+ Git
https://code.visualstudio.com/docs/editor/versioncontrol


```
git clone git@github.com:trivalleymath/website.git
git submodule update --init --recursive

git add <file>
git commit -m "comment"
git status
git push origin master

```

Convert image from PNG into SVG

```
inkscape -z -l mystic-mountain.svg mystic-mountain.png
```

Add a new post

```
hugo new posts/new-post.md
```

Start local server in debug mode
```
hugo server -D
```

Update submodule

```
git config --file=.gitmodules -e

git submodule sync
git submodule update --init --recursive --remote
```