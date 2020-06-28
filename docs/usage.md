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
