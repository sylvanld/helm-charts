# Quickstart

This github pages site hosts [helm charts](https://helm.sh/docs/) published by organization [sylvanld](https://github.com/sylvanld).

## Configure repository

```bash
helm repo add sylvanld "https://sylvanld.github.io/helm-charts/"
```

## List charts from this repository

Either have a look at charts section from this documentation or use helm:

```bash
helm search repo sylvanld
```

## Install a chart from this repository

To install a chart from this repository, example given `octoauth`, run the following:

```bash
helm install octoauth sylvanld/octoauth
```
