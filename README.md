# Readme

### How is this website being deployed?

-   Using netflify and its deploy from github option - <https://bookdown.org/yihui/blogdown/netlify.html>

  - Clicked on **New site from Git** after setting up repo and serving the site for the 1st time (see below) <https://app.netlify.com/teams/j450h1/overview>
  
  - Setup a file called netlify.toml (as per recommendations when setting up new connection)

### What is the workflow?

-   Make updates locally

-   `blogdown::serve_site()`

-   Push changes to github

-   Netlify should see the changes and update the website
