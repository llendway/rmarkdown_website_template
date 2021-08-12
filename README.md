# Template for creating an RMarkdown website

This contains a base set of files you need for making an RMarkdown website.

* Make sure the .Rmd file in the main directory of the project is named index.Rmd. 

* The other .Rmd files can have any name you'd like but need to remain in the main directory. Although it might help organize the file structure, these files cannot be in a folder. 

* The `_site` folder and `_site.yml` file need to be named exactly as they are. The `_site` folder is initially empty, but once you build the site, it will be populated with the .html files knitted from the .Rmd files that are in the main directory.

* Within the `_site.yml` file, the `href`s correspond to the names of the knitted .html files.
