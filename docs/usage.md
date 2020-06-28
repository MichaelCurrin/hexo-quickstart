# Usage

This uses the scripts commands configured in [package.json](/package.json) - those were mostly generated with the `init` command.

## Run dev server

Start server:

```sh
$ yarn server
```

Open the browser at:

- http://localhost:4000

The server will rebuild on file changes but you'll have to refresh the browser to see changes.

Note that this runs in memory - there is no output directory yet.

## Build

```sh
$ yarn build
```

Then view the the `public` directory in the repo.

## Clean

According to the docs, this cleans the cache file (`db.json`) and generated files (`public/`).

```sh
$ yarn clean
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

<details>
<summary>

```
Usage: hexo <command>
```

</summary>

```
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

</details>


For more info see the [Commands](https://hexo.io/docs/commands) section of the Hexo docs.
