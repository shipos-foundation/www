# shipOS

This is the home of the shipOS landing page

[![Netlify Status](https://api.netlify.com/api/v1/badges/4e5f76c7-c43c-4ea6-bedf-1ad4cd3aea3d/deploy-status)](https://app.netlify.com/sites/shipos/deploys)


## Cloning

This repository has sub modules, clone it with:

```shell
$ git clone --recursive <repository url>
```

If you've already cloned it, you can get the submodules by doing the following:

```shell
$ git submodule update --init --recursive
```

## Running

This page is built on top of [Hugo](http://gohugo.io/).
In order to run the page locally and work it, you'll have to [install Hugo](https://gohugo.io/getting-started/installing/)
first and then in your CLI, navigate to the `Source` folder in this repo and
do:

```shell
$ hugo server
```

You can then navigate with your browser to the address shown.
With the server running you can edit any file, add new content and
when saving the browser should automatically refresh.
