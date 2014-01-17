## Radiant: Business analytics using R and Shiny

Interactive business analytics using [R](http://www.r-project.org/) and [Shiny](http://www.rstudio.com/shiny/). Developed by [Vincent Nijs](http://rady.ucsd.edu/faculty/directory/nijs/) (vnijs@rady.ucsd.edu). 

### Todo:

- Restructure into a modular R-package
- Use dplyr to explore and summarize data
- Code documentation
- Testing
- etc. etc.

### Install 

- Required: [R](http://cran.rstudio.com/), version 3.0.2 or later
- Required: [Shiny](http://www.rstudio.com/shiny/), version 0.8.0.99 or later
- Required: A modern browser (e.g., Chrome or Safari)
- Suggested: [Rstudio](http://www.rstudio.com/ide/download/)

Currently Radiant requires the development version of Shiny. On Windows you will need [Rtools](http://cran.r-project.org/bin/windows/Rtools/). On Mac, make sure you have XCode (free, available in the app store) and the "Command Line Tools for Xcode" (Xcode > Preferences > Downloads).

To install the development version of Shiny follow the steps below:

	options(repos = c(CRAN = "http://cran.rstudio.com"))
	install.packages('devtools', repos = "http://cran.rstudio.com")
	require(devtools)
	install_github('shiny','rstudio')
	require(shiny)

To install and run the Marketing analytics app in Radiant:

	install_github('radiant','mostly-harmless')
	runApp(system.file("marketing", package="radiant"))

<!-- 
To get the app click the 'Download ZIP' button and unzip the file to, for example, your Desktop. When you start the app for the first time a number of required packages will be installed. To start the app, copy and paste the command below into the R(studio) terminal (assuming you unzipped to your Desktop):

	# on windows
	shiny::runApp('~/../Desktop/radiant-master/inst/marketing/')

 	# on mac
	shiny::runApp('~/Desktop/radiant-master/inst/marketing/')
 -->

### License

The Radiant package is licensed under the [AGPLv3](http://www.tldrlegal.com/l/AGPL3). The help files are licensed under the creative commons attribution non-commercial license [CC-NC-SA](http://www.tldrlegal.com/license/creative-commons-attribution-noncommercial-sharealike-(cc-nc-sa)). 

As a summary, the AGPLv3 license requires, attribution, include copyright and license in copies of the software, state changes if you modify the code, and disclose all source code. Details are in the COPYING file.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>

If you are interested in using Radiant please email me at vnijs@rady.ucsd.edu

&copy; Vincent Nijs (2014)
