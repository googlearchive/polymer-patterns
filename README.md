# Polymer Snippets

Small, useful, snippets/samples that show how to do things the Polymer way.

## Setup

    bower install

### Run the tests

1. Fire up a web server in the root of this repo. For example:

    python -m SimpleHTTPServer

2. Hit [http://localhost:8000/tests/](http://localhost:8000/tests/).


## Repo structure

All snippets go in `snippets/` and all tests go in `tests/`.

### Snippets

The snippets should be short and atomic.

Use the following format for a snippet `.html` file:

* License
* Documentation:
    * Title
    * A one-line description of what the snippet does
    * Short discussion
    * Link to official docs
    * JSBin link
* Code

Snippet filenames begin with action verbs. For example:

    snippets/control-flow/using_conditional_tempalates.html

### Tests

We use mocha with chai asserts for testing. All tests go in `tests/` with one
`.html` file per test. Make sure that the name of the test file is the same as
the snippet file. For example:

  snippets/control-flow/using_conditional_tempalates.html
  tests/using_conditional_tempalates.html

Be sure to add the test file to `tests/all.html`.

Tests are *required** for each recipe.
