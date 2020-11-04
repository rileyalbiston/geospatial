
Link to Site:

[https://rileyalbiston.github.io/geospatial](https://rileyalbiston.github.io/geospatial)

## Website Structure

**Main Menu Items**

* Home/About Me - Shows basic profile (use same paragraph as LinkedIn profile)
* Resume
* GIS Portfolio
* Blog
* Resources

**GIS Portfolio Page**

Simple description of each project. Outline what it demostrates (skills, problems solved etc). Main goal is the highlight maps and dashboards.
Have links to the full project right up on the blog and/or to the github repo

**Blog**

For full detailed expaination of project, including code samples and screen shots. Maybe be written as a tutorial or project outline.

Project outlines will include:

* Aims and Objectives
* Links to Data Sources
* Considerations
* Step by step how-to with code samples
* Future work that could expand the project

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