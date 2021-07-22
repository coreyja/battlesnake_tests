# battlesnake_tests
A collection of battlesnake JSON states along with their expected move.  Feel free to use this to test any of your battlesnakes.

# Format

Under the `tests` directory, there is a sub-directory for each test. The tests are currently numbered, but any sub-directory will work.

In each 'test directory' will be TWO files:
 - `input.json` which is the body which should be sent to the `/move` endpoint
 - `output.json` which is the expected output
