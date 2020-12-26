# Personal blog

Source code for my personal blog.

## Setup

```bash
hugo version
hugo new site portfolio
cd portfolio/
git init
git submodule add https://github.com/StaticMania/portio-hugo themes/portio
cp -a themes/portio/exampleSite/* .
hugo serve
git add --all
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/cseas/portfolio.git
git push -u origin main
```
