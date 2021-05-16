# Code review checklist

This is a sample code review form that is meant to make the process easier for newcomers.
Feel free to reuse it for your project.

The goal of the code review is to ensure that proposed changes fit in the codebase nicely. If you are not sure where to start, examine the code and try to answer some of these questions:

## Functionality

[ ]  I have tested the change, it builds and works for me (if possible, supply sample data and steps to reproduce the success)

[ ] The code implements the functionality as it's described in the feature request and/or commit description.

[ ] I like the change and want it merged.


If you object to merging the change:

* The change fails to build on the following setup: <insert your build environment here>
* The change fails to work as described under following circumstances: <describe the reproducing steps>
  
## Style

[ ] The code meets the coding style guidelines.

If you object:

* The code violates the following guidelines: ...

## Compatibility

[ ] This change breaks compatibility with older versions in the following ways: ...

[ ] This change breaks compatibility with following third-party systems: ...

[ ] This change breaks compatibility with the following standards: ...

## Design

[ ] This change will make implementing the following features harder in the future: ...
