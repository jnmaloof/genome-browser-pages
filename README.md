genome-browser-pages
====================

This is a repository for the html and DAS stylesheets that specify the [Maloof Lab Genome Browser](http://symposium.plb.ucdavis.edu/genome-browser/pages)

The Maloof Lab Browswer is powered by [dalliance](http://biodalliance.org)

The data files for the repository are not included here--they are too big.  But you don't need them because they are served off of the maloof lab site

## Setting up your own copy of this browser.

If you want to up your own fully-functional version of this browser:

### get all of the files

    mkdir mysite #can use anyname
    cd mysite
    wget https://github.com/twbs/bootstrap/releases/download/v3.3.1/bootstrap-3.3.1-dist.zip
    unzip bootstrap-3.3.1-dist.zip
    git clone https://github.com/dasmoth/dalliance.git
    git clone https://github.com/jnmaloof/genome-browser-pages.git
    
### build dalliance

First install [node.js](http://nodejs.org/)

The `cd dalliance` and follow the instructions in the README.md there

