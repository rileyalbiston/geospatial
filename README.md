## Categories

* postgis
* python / geopandas
* qgis

## Pelican Static Site Generator Documentation

[Pelican Static Site Generator Documentation](https://docs.getpelican.com/en/stable/)

## Start Dev Server on local machine

```pelican --listen```

[http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Build Development Page

```pelican content -s pelicanconf.py -o output -t theme```

## Build Production Page

```pelican content -s publishconf.py -o output -t theme```

## Push to GitHub main Branch

1.
 
```git status```

2.

```git add *```

3.

```git commit -m "message"```

4.

```git push```

## Use ghp-import to push to the gh-pages brach

1. 

```ghp-import output```

2.

```git push origin gh-pages```