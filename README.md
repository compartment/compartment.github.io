# CompartmentCMS.com

This repository serves as the main landing page at CompartmentCMS.com. It is powered by the [Jekyll static site generator](http://jekyllrb.com).

## Getting Started

Begin by cloning the repository:

    git clone git@github.com/compartment/compartment.github.io ~/compartmentcms.com

Assuming you already have Ruby installed, run `gem install jekyll` to install the jekyll gem.

Now start the jekyll server to view the site in your browser:

    cd compartmentcms.com
    jekyll serve --watch

Open your browser to see the website:

    open http://localhost:4000

Press `control+c` to stop the server.

If you're already using port 4000, you can specify a different port using the `-P` option:

    jekyll serve --watch -P 4001
