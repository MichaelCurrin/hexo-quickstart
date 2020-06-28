# Hexo Quickstart
> The easy way to start create a new Hexo blog


Hexo is a static-site generator which can be installed as an NPM package.


## Purpose

- Basic intro/tutorial
- Template project
- Live demo on GH PAges



## Requirements

- Node.js
- Yarn


## Create a fresh project

Use `npx` to download and run `hexo` in one command.

```sh
$ npx hexo init my-project
$ cd my-project
```

Or use an existing project as below.


## Install

Clone this repo.

Then run:

```sh
$ yarn install
```


## Usage

This uses the scripts commands configured in [package.json](/package.json) - those were mostly generated with the `init` command.

### Dev server

```sh
$ yarn server
```

Open the browser at:

- http://localhost:4000

The server will rebuild on file changes but you'll have to refresh the browser to see changes.

### Build

```sh
$ yarn build
```

### Clean

```sh
$ yarn clean
```

From docs:

> Cleans the cache file (db.json) and generated files (public).

### Deploy

Deploy only

```sh
$ yarn deploy
```

Clean, generate and then deploy. This is not a standard command but was added for convenience.

```sh
$ yarn deploy-full
```


## Hexo CLI


If installed in project:

```sh
$ node_modules/.bin/hexo --help
```

If installed globally:

```sh
$ hexo --help
```

Sample output:

```
Usage: hexo <command>

Commands:
  clean     Remove generated files and cache.
  config    Get or set configurations.
  deploy    Deploy your website.
  generate  Generate static files.
  help      Get help on a command.
  init      Create a new Hexo folder.
  list      List the information of the site
  migrate   Migrate your site from other system to Hexo.
  new       Create a new post.
  publish   Moves a draft post from _drafts to _posts folder.
  render    Render files with renderer plugins.
  server    Start the server.
  version   Display version information.
```


For more info see the [Commands](https://hexo.io/docs/commands) section of the Hexo docs.



## Resources

- [hexo.io](https://hexo.io/) homepage
- [Hexo docs](https://hexo.io/docs/) homepage
    - [Setup](https://hexo.io/docs/setup)
    - [Commands](https://hexo.io/docs/commands)
    - [Generating](https://hexo.io/docs/generating)
    - [Writing](https://hexo.io/docs/writing.html)
        ```sh
        $ hexo new 'My new post'
        ```

### Deploy

- [Deploy command](https://hexo.io/docs/commands#deploy)
    ```sh
    $ hexo deploy

    $ hexo deploy --generate
    ```
- [Github Pages](https://hexo.io/docs/github-pages)
- [One-command deployment](https://hexo.io/docs/one-command-deployment.html)
    - This covers Zeit, Netlify, Heroku and more.
