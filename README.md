[![Build Status](https://travis-ci.org/patrickneubauer/eclipse-tycho-example.svg?branch=master)](https://travis-ci.org/patrickneubauer/eclipse-tycho-example)
# eclipse-tycho-example
Eclipse Tycho example for creating Eclipse plugins, OSGi bundles, and Eclipse RCP applications

HOW TO USE:
-----------

1. Clone repository.

2. First, import maven projects to Eclipse workspace as Maven projects using the Eclipse "Existing Maven projects" dialog.

3. Execute Eclipse run-configuration named "com.patrickneubauer.examples.tycho BUILD.launch" to build the project.

4. Execute Eclipse run-configuration named "com.patrickneubauer.examples.tycho RUN.launch" to run Tycho RCP application.


TESTED ON:
----------

Eclipse Modeling Tools, Version: Oxygen Release (4.7.0), Build id: 20170620-1800

OS: macOS High Sierra (10.13.6)

Maven: 3.3.9 (Eclipse Oxygen embedded) and 3.5.0 (homebrew)


BASED ON WORK BY LARS VOGEL:
----------------------------

* [Eclipse Tycho for building plug-ins, OSGi bundles and Eclipse applications - Tutorial](http://www.vogella.com/tutorials/EclipseTycho/article.html)

* [Eclipse Target Platform - Tutorial](http://www.vogella.com/tutorials/EclipseTargetPlatform/article.html)

* [Eclipse product and application deployment - Tutorial](http://www.vogella.com/tutorials/EclipseProductDeployment/article.html)
