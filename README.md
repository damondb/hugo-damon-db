# hugo-damon-db

## Features

## Installation

Install Hugo and create a new site. See [the Hugo documentation](https://gohugo.io/getting-started/quick-start/) for details.

### Git Submodule

Add hugo-damon-db as git submodule:

    $ git submodule add https://github.com/damon-db/hugo-damon-db.git themes/hugo-damon-db

### Hugo module

Initialize your site as hugo module:

    $ hugo mod init github.com/USERNAME/SITENAME

Add hugo-damon-db module as a dependency of your site:

    $ hugo mod get github.com/damon-db/hugo-damon-db

### Site preview

Copy the content of `exampleSite` at the root of your project:

    cp -r themes/hugo-damon-db/exampleSite/* . -iv

If you installed hugo-damon-db as hugo module, set your theme in your config file (hugo.toml):

    [[module.imports]]
      path = "github.com/damon-db/hugo-damon-db"

Start Hugo:

    hugo serve

Open the site at `localhost:1313`

Note: Using `127.0.0.1` instead of `localhost` will not work due to CORS issues.


## Configuration
