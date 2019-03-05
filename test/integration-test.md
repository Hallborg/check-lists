## Check list for writing integration tests ##

Unit tests should already be in place.
You probably have an idea of how the units should interact.
Write as much as you can into tests.

- Mock all dependencies that should not be a part of the integration tests.

- Single concept for each test.

- Make it readable by extracting private functions.

- Minimize the number of tests. Do you have anything that is already
  covered in unit tests?