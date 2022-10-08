= Slide Development

== Setup
Before the development can start we need to have ruby installed and run ´bundler install´.
To generate the pdf slides we optionally need [decktape](https://github.com/astefanutti/decktape) which can be installed via npm.

== Slide Generation
With the asciidoc-present utility we can simply generate the slides by typing ´./asciidoc-present b´.
This command generates all slides present under _src_ into __dict_ directory in own directories.
To present simply open the _index.html_ in a browser and use the arrow key to navigate.

== PDF Generation
With the asciidoc-present utility we can generate pdf the slides all at once or a specific talk.
´./asciidoc-present pa´ generates all talks into the __print_ directory.
With ´./asciidoc-present p <name>´ the utility generates the pdf to the talk with name _name_.

== Other Operations
All possible operations are shown with their documentations by typing ´./asciidoc-present h´.