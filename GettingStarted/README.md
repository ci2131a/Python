## Getting Started

Reference this section for notes to setup Python on your computer.

### Download Python

The download for Python is free and can be done through the website. You can find the latest stable release [here](https://www.python.org/downloads/). Download the program for your relevant operating system or compile the source code manually. 

### Picking an IDE

An **Integrated Development Environment (IDE)** is a specific type of text editor that can be used when programming. Selecting an IDE is an important task as these are programs with which you can edit text but more specifically edit the code you have written. Most of the code you write is going to be contained in a **script** which is a file that contains code waiting to be executed. The IDE will open the script file and allow you to mark it. Most IDEs also have the ability to check your code for any typos which is called a **syntax error**. Additionally, they allow you to run your code and display the output to you. While an advanced IDE is not required, it is strongly encouraged. 

One benefit of Python is that is comes with an IDE! The Python IDE is called IDLE and comes bundled with the default download of the program. Following the download steps from the previous section will give you access to IDLE. Tips to use IDLE are discussed in the next section. Some other notable IDEs for Python include but are not limited to Spyder, Jupyter Notebook, Anaconda, and Visual Studio Code. A comprehensive list of Python IDEs can be found through Python's Wiki [here](https://wiki.python.org/moin/PythonEditors).

A last note on IDEs: it is possible to use a generic text editor to make changes to your code. These will not allow you to check for errors nor run your code but can be used in extreme circumstances. 

#### IDLE

#### RStudio

One unusual IDE for Python is RStudio. Recently, the RStudio organization has been making a push to make its IDE a comprehensive program for use in data science. As noted in the top README, Python has wide applications to data science with methods to perform a number of processing and analysis techniques. However, RStudio was primarily designed for R which is a statistical programming language not generally used by traditional computer scientists nor Python programmers. So, why mention this as a possible IDE if it is not widely used? Well, the author of this repository is a statistician and uses R and RStudio quite regularly. Therefore, most of the Python in this repository was done through R and RStudio. If you are interested in using R and RStudio in addition to Python, follow the steps provided in the next paragraph to set up all 3 components. Otherwise, you can skip to the next section. (I mostly wanted to take this opportunity to plug R and RStudio ;) .)


R & RStudio

```{r}
install.packages("reticulate")
reticulate::

reticulate::repl_python()
```


```{python}
exit
```

See documentation for the R reticulate package for more information. 