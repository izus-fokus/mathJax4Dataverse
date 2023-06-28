# mathJax4Dataverse

This repository consists of a script (customJax.js) to process specific HTML elements by mathjax and convert LaTeX code with mathematical formulas into pretty rendered math equations. This script can be tested with the example.html page and integrated into a Dataverse installation via [a custom footer](https://guides.dataverse.org/en/latest/installation/config.html#custom-footer) (custom-footer-js.html)

### >> Steps to add script to required HTML file: 
   1. Add the following code to the required HTML file: 
```javascript 
    <script src="/path/to/customJax.js"></script>
    <script> addEventListener('DOMContentLoaded', (event) => {
        convertcdn();
        convert(); 
      });
    </script> 
 ```

