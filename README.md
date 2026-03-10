# Webpage redesign notes

-   Use a standard framework that you can trust to keep up on accessibility. At the moment, Quarto is the frontrunner.

-   Design for deployment using ghpages and GitHub actions:
    -   on push to GitHub, an action should build the website and push it to the gh-pages branch

-   Design for redundant deployment using a self-hosted git repo and hooks:
    -   on push to repo, a hook should build the website and push it to hosted directory

-   Design with possible future plans for a non-static self-hosted deployment?

-   Design for react.js slide generation/hosting for research talks and teaching
    -   automatic generation of html slides with fixed theme/plugins
    -   automatic generation of PDF slides

-   Generate/host handouts for talks and teaching in both HTML and PDF formats

-   Logic textbook should be separate, but share the same basic design
    -   with future plans to self-host both together on the same server?

-   automatic generation of pdf version of CV

-   Host html/audio/audio+slideshow versions of research papers?




