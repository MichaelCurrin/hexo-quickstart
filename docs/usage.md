# Usage
> Run the project locally

This uses the scripts commands configured in [package.json](/package.json) - those were mostly generated with the `init` command.


## Run dev server

Start server:

```sh
$ yarn server
```

Normally the command would be `start` or `dev` - that can easily be set in the commands instead.

Open the browser at:

- http://localhost:4000/hexo-quickstart/

The server will _rebuild_ on file changes but you'll have to refresh the browser to see changes.

If you make any  [config](/_config.yml) file changes like changing the subpath, you will have to stop and start the server.

Note that this dev site runs in memory - there is no output directory yet.


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
