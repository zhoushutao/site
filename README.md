# 叔弢遗事

## Quick Start

 1. Download [Hugo Releases](https://github.com/gohugoio/hugo/releases) and add to your `$PATH`.
 1. Create new repo `site`.
 1. Clone your _site_ to local.
 1. `hugo new site temp`, then `cp` all files to the repo root.
 1. Add theme, for example `git submodule add https://github.com/olOwOlo/hugo-theme-even themes/even`.
 1. `git submodule add https://github.com/zhoushutao/zhoushutao.github.io.git public`
 1. Preview the site `hugo serve -D`

## Integrate With GitHub Pages

 1. `git submodule add --force -b master git@github.com:zhoushutao/zhoushutao.github.io.git public`
 1. `hugo` build project.
 1. `sh deploy.sh`
 
## Clear Submodules
 1. `git submodule deinit -f -- public`
 1. `git rm -f public`