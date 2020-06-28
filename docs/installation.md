# Installation
> Install the project locally

## Install system dependencies

Install Node.js and Yarn - see [gist](https://gist.github.com/MichaelCurrin/bdc34c554fa3023ee81449eb77375fcb) instructions.


## Clone

Clone this repo. Use the `--recursive` flag to include the theme submodule.

- HTTP
    ```sh
    $ git clone --recursive https://github.com/MichaelCurrin/hexo-quickstart
    ```
- SSH
    ```sh
    $ git clone --recursivegit@github.com:MichaelCurrin/hexo-quickstart.git
    ```

```sh
$ cd hexo-quickstart
```


## Install project dependencies

```sh
$ yarn install
```


## Install Hexo globally

This is not needed as the quickstart has Hexo in the package file and a new project can be created using `npx`.

But, if you want to install Hexo globally, do this:

```sh
$ npm install hexo-cli -g
```
