## Introduction to Python and IPython Notebooks

Begin by cloning this repo to a new directory on your computer.

* Make a new directory
* Open a Command Tool (Windows) or Terminal (Mac, Linux)
* type `git clone ` and then the url noted on the right of this window.


To use iPython Notebooks, always do the following:  

1. Navigate to the folder where the notebook(s) are located
2. Open a Command Tool in that folder
    * shift-right-click to get the following menu
    * then select `Open command window here`
    
    ![cmd_tool](pix/win_cmd_tool.png)
    
3. go to the new command tool and type

    ```
    ipython notebook --pylab inline
    ```

4. A browser should pop open to the "iPython Dashboard"
    * if a browser does not open, look in the command tool window for a line that says something like `The Ipython Notebook is running at: http://...`
    * copy the web address and paste it into the search bar of any browser to see the ipython dashboard
    
### Some things to keep in mind:

* Create new notebooks by clicking the "New Notebook" button in the iPython Dashboard
* You will see that each new notebook is named like "Untitled" and a number.
    * __Immediately__ click on that name, and change it to something meaningful
* Use ctrl-S to save
* _There is NO UNDO_ in the IPython notebook environment. 
    * Save frequently
    * Use version control
* Any iPython Dashboard refers only to notebooks located in one particular folder. You can not use the dashboard to open notebooks spread around your file system.
* Be sure to save (ctrl-s) each notebook before closing its browser tab
* Ideally, click the "Shutdown" button next to each notebook when you are done with it, BUT
    * Be careful not to accidentally click "Delete" --- it's the same button!
* You shut down the entire notebook by going back to the command tool that launched it, and entering ctrl-c

### Good introductory resources

* [IPython Notebook official documentation](http://ipython.org/ipython-doc/stable/interactive/notebook.html)
* [A Gallery of Interesting IPython Notebooks](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks)
* [A Crash Course in Python for Scientists](http://nbviewer.ipython.org/5920182)
* [Python for Data Analysis book and website](http://nbviewer.ipython.org/urls/gist.github.com/wesm/4757075/raw/a72d3450ad4924d0e74fb57c9f62d1d895ea4574/PandasTour.ipynb)
* [A 10 minute video tour of Pandas by Wes McKinney](http://vimeo.com/59324550)
