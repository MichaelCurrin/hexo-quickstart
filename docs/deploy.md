# Deploy


## CI deploy

This project comes with a super simple [workflow file](/.github/workflows/main.yml) for Github Actions.

It does a generic Yarn build.

Then uses [peaceiris/actions-gh-pages](https://github.com/peaceiris/actions-gh-pages) to commit to `gh-pages` branch, so it can be served with Github Pages.

This will happen automatically when committing to the repo's `master` branch.

The catch is that after the first GH Pages deploy, you need to go into the repo _Settings_ and change the Github Pages setting to another setting and then back to `gh-pages`. Then it will serve properly. This change is only needed once.


## Alternatives

If for some reason the current approach is too limiting for you, you can try one of these actions which specialize in Hexo deploys.

- [hexo-action](https://github.com/marketplace/actions/hexo-action)
- [hexo-github-action](https://github.com/marketplace/actions/hexo-github-action)
- [github-action-for-hexo](https://github.com/marketplace/actions/github-action-for-hexo)


## Run deploy command locally

If you deploy to Github Pages and use the [CI Deploy](#ci-deploy) section above there is no need to use the deploy command locally. This is covered here for completeness though.


### Configure

First setup a deploy config file as per [Resources](resources.md#deploy).

Then run one of these commands locally.

### Build and deploy

This will build the `public` directory and deploy it.

```sh
$ yarn clean
$ yarn build
$ yarn deploy
```
