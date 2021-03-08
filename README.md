# Install Jekyll to work on this repository
How to install Jekyll on Ubuntu: https://jekyllrb.com/docs/installation/ubuntu/ 

# Creative Theme for Jekyll

A Jekyll implementation of the [Creative Theme](http://startbootstrap.com/template-overviews/creative/) template by [Start Bootstrap](http://startbootstrap.com).

Creative is a one page Bootstrap theme for creatives, small businesses, and other multipurpose uses.
The theme includes a number of rich features and plugins that you can use as a great boilerplate for your next Jekyll project! 

See it live in action at <https://volny.github.io/creative-theme-jekyll/>

## To use the Creative Theme template in your project

- Start by adding your info in `_config.yml`
- In `_layouts/front.html` reorder or remove section as you prefer.

# Upload changes to be available in https://frostforecast.cl/
To include new code changes to be available in the public Frost web site, follow the instructions below:

1. Make the changes in a branch from "main" and then, add and commit them as usual. After that, do `git push origin <branch-name>`.

2. Create the Pull Request to merge the branch into "main".

3. Once the branch is merged in "main", in local command line, go to folder /_site with `cd _site`. In that moment the current branch should be "gh-pages"* (to check that do `git branch`).

4. In the branch "gh-pages", add and commit the changes again with `git add <file>` and `git commit -m <message>` and, finally `git push origin gh-pages`.

5. Wait until https://frostforecast.cl/ updates.

*"gh-pages" branch creation is based on http://sangsoonam.github.io/2019/02/08/using-git-worktree-to-deploy-github-pages.html
