##Website for Hays and Skerry law firm

Website is under active development. You can view a dev version [here] (http://askerry.github.io/dad_site/).

###Developers
- Greg Skerry
- Amy Skerry

###Tools:
- Hyde
- Less
- Bootstrap (less mixins)

###Notes:
- contact form relies on hacky workaround that piggybacks on an [external plugin](https://www.wufoo.com/)

- dev hosting is on gh-pages
   1. make branch gh-pages containing only the deploy directory of the repo (git subtree split --prefix deploy -b gh-pages)
   2. push the gh-pages branch to the gh-pages branch on github (git push -f origin gh-pages:gh-pages)

