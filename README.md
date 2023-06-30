# mathJax4Dataverse

This repository consists of a script (customJax.js) to process specific HTML elements by mathjax and convert LaTeX code with mathematical formulas into pretty rendered math equations. This script can be tested with the example.html page and integrated into a Dataverse installation via [a custom footer](https://guides.dataverse.org/en/latest/installation/config.html#custom-footer) (custom-footer-js.html). The custom footer file renders LaTeX code in the metadata fields **Title** and **Description** (for this, we are using HTML-Elements with the ids "title", "dsDescription", "metadata_title", "metadata_dsDescription", see line 11 in custom-footer-js.html to change). 


