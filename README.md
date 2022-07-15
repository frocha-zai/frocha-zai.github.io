# data-documentaion-test
* used tutorial found here: 
    * part 0: https://www.youtube.com/watch?v=_xDgNKc6-AI
    * part 1: https://www.youtube.com/watch?v=WcUhGT4rs5o
    * part 2: https://www.youtube.com/watch?v=RvJ54ADcVno

# TO DO
* look for professional template for readme
* what is the most effective structre to combine multiple servers, svhema, tables
    * server / schema / tables



# Manage Sphnix project 
## Create and setup a Sphnix project
* install sphinx
* run in the terminal: sphnix-quickstart
* a set of files/folders will be added 


## Develop project
* run in terminal make html to build the documentation page. The html page is located under build/ folder
    * over the development process, sometimes you may notice that old pages still appears. That is stored at build folder and may not have been removed and you re-built. You may use m -R build ; make html to delete the build folder and to build again the project.
* to check the result in the browser, run in the terminal: open -a"Google chrome" build/html/index.html 
* update theme
    * https://www.sphinx-doc.org/en/master/usage/theming.html
    * go to source/config.py, update html_theme = "sphinx_rtd_theme"
* at video part 3 shows how to add image, tag/anchor to a page, add links etc

* explain logic (nested toc tree) to arrange server - schema - tables
* update
