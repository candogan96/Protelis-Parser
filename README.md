# Protelis-Parser
Parser for Protelis, the practical aggregate programming language

## How to Build in Eclipse:

There are six sub-projects in this repository, all of which should be
imported into Eclipse.

* alchemist.protelis.parent:
  the build point, which should pull in all of the others
* alchemist.protelis
  specifies the Protelis DSL and associated utilities using XText
* alchemist.protelis.target:
  specifies the Eclipse runtime environment that the DSL plugin should
  be compatible with.
* alchemist.protelis.ui:
  Contains the Eclipse plugin to support Protelis editing
* alchemist.protelis.repository:
  Packages for the automated install website for Eclipse
* alchemist.protelis.tests:
  Makes sure that you can fire up an instance of Eclipse that can
  load the plugin

Then what?
How do we know if it worked?

## Dealing with build problems
Maven: plugin lifecycle should be warning, no error
  Change this in Eclipse Preferences > Maven >

Maven needs to be at least version 3.3.3
