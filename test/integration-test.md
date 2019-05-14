## Check list for writing integration tests ##

Integration: ~ Assembling units to interact together to create meaning ~

You probably have an idea of how the units should interact.

#### Mock:
 - mock all dependencies that should not be a part of the integration tests.

#### Single concept:
 - All tests should test one thing. This must be visible from the test name.

#### Independent:
 - States should not persist after a test.
 - Enabling running a test in isolation.

#### Readable:
  - Extract private functions or move repeated functionality into help classes.
  - Structure the tests using the Build-Operate-Check principle (or similar).

#### Repeatable:
  - Run locally; this is the easy part.
  - Run in dedicated remote environment; What needs to be installed?
  - Run without internet connection.

#### Minimize:
  - Do you have anything that is already covered in unit tests?
  - Fewer tests means faster feedback loops.
