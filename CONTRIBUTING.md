# Contributing

## Repo structure

All snippets go in `snippets/` and all tests go in `tests/`.

### Snippets

Each snippet should be short and atomic, and it should help developers solve
a specific problem.

Use the following format for a snippet `.html` file:

* License
* Documentation:
    * Title
    * A one-line description of what the snippet does
    * Short discussion
    * Link to official docs
    * JSBin link
* Code


#### Naming conventions

Snippet filenames should begin with action verbs. For example:

    snippets/control-flow/using-conditional-templates.html

Use dashes (`-`), not underscores (`_`) in directory and file names.

### Tests

We use mocha with chai asserts for testing. All tests go in `tests/` with one
`.html` file per test. Make sure that the name of the test file is the same as
the snippet file. For example:

  snippets/control-flow/using-conditional-tempalates.html
  tests/control-flow/using-conditional-tempalates.html

Be sure to add the test file to `tests/all.html`.

Tests are **required** for each recipe.


