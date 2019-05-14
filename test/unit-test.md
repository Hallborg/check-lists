## Check list for writing unit test ##

Unit: ~ Entity regarded as a structural or functional constituent of a whole ~

Remember to use baby steps. compile-test-commit.  
Both for TDD, and 'only' unit test writing.

#### Unit:
  - Drive your test by behavior.
  - Do not test implementation details. Refactoring will break such tests.

#### Mock:
  - Use mocks to make your tests faster or cleaner. Http clients and databases
    connections are good candidates.  

#### Code Coverage:
  - Achieve 100% coverage of the code under test. Enables refactoring.
  - Don't rely to much on coverage, behavior is more important.

#### Boundaries:
  - Test all boundaries. Still most error prone.

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
