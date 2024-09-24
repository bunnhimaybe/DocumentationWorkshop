Sphinx Documentation
========================
Python must be installed. The recommended download is Python 3+ but Python 2.7 is fine. 
In Windows, make sure the 'pip' and 'PATH' boxes during download installation is checked.

To check if python downloaded correctly, run the following commands based on the operating system (OS) used in your command or terminal line.

* Windows:
    * ``$ py --version``
* MacOS:
    * ``$ python3``

To install Sphinx, run the following commands:

* Windows:
    * ``$ pip install -U sphinx``
* Linux:
    * ``$ apt-get install python3-sphinx``
* MacOS:
    * ``$ brew install sphinx-doc``

Git Repository
-------------------------------
Git clone the reposity into your documents folder.
 * https://github.com/bunnhimaybe/DocumentationWorkshop.git

Folder and Document Information
---------------------------------
* DocumentationWorkshop.sphinx
    * README.rst: information about the folder and files
    * .venv: supports the creation of a virtual environment, allows developers to control software dependendies such as packages and libraries
        * docs: location of your build and source directory folders
            * build
                * doctrees: shows the specific content in each doctrees
            * html
                * creation of webpages
                * index is your main root file, click this documentation to see the entire information 
                    * The Sphinx Documentation is found in this file

* index.rst: main page
    * Header: Sphinx Documentation
    * subHeader(s): Overview, Definition, Navigation 
* usage.rst: second content page
    * Header: Installaton and Environment
    * subHeader(s): How to Install Sphinx, How to Set-Up Environment
* customisation.rst: third content page
    * Header: Customisation
    * subHeader: restructuredText and Markdowns, Paragraph Markups, Objects, See also and Change

Pathway to find HTML
--------------------------------
C Drive > Users > [YourFolder] > [CreateFolder]​ > [.venv] > [docs] > [index]
