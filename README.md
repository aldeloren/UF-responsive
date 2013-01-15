Responsive style
================
University of Florida static HTML template
------------------------------------------
> Author: Anthony DeLorenzo
> Version: .1 (pre-alpha)
> Date: 15 Jan 2013
To enable a responsive layout to your static HTML website based on the University of Florida [ufl.edu](http://ufl.edu) follow the directions below.

### Getting started
Please note: this is a word in progress, and *will* have bugs. Please send an email to [the author](mailto:aldelorenzo@ufl.edu) with any questions, fixes, or suggestions. 

### Dowload the template
If you are installing a fresh version of the UF template, you will not need to follow steps 1-3. 

#### Download link
Download the files. They can be found in the UF webservices repo, or the [Web Services website](webservices.it.ufl.edu/https://webservices.it.ufl.edu/uf-template/downloads/).

Included in the responsive theme download you will find these files:
-responsive.css
-scripts.js
-scripts.html
-nav-sidebar.html
-head-begin.html
-/images/(coming soon)

#### Add files
With the exception of responsive.css, all of these files already appear in the UF theme. If you are using the theme with little modification you can simply replace the files that exist already in their respective directories (listed below). If not, follow the well documented comments within each of the files. 

    File directory:
    -responsive.css move to --> /_library/css/
    -scripts.js move to --> /_library/js/
    -nav-sidebar.html move to --> /_includes/
    -header-begin.html move to --> /_includes/

#### Customize
The theme is responsive with the standard elements of the UF theme. If you have added customizations, you will have to style those elements yourself by adding styles to responsive.css

Additionally, the theme is responsive under 800 pixels wide. This width excludes most modern tablets which are capable of viewing a website at full resolution. Older 10" tablets, some 7" tablets, and most smartphones will see the responsive layout. If you wish to change this so that most tablets (including iPad 3 and above) modify the below line of HTML in header-begin.html:

    <link rel="stylesheet" media="screen and (max-width: 760px)" href="/_library/css/responsive.css">
    to
    <link rel="stylesheet" media="screen and (max-width: 1030px)" href="/_library/css/responsive.css">

