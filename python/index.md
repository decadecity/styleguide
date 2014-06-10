# Python

In general Python code follows PEP8: http://legacy.python.org/dev/peps/pep-0008/

(Much of what follows is taken from PEP8)

Code is indented using four spaces.

Closing brace/bracket/parenthesis on multi-line constructs is lined up under the first character of the line that starts the multi-line construct, as in:

    my_list = [
        1, 2, 3,
        4, 5, 6,
    ]
    result = some_function_that_takes_arguments(
        'a', 'b', 'c',
        'd', 'e', 'f',
    )

## Blank Lines

Separate top-level function and class definitions with two blank lines.

Method definitions inside a class are separated by a single blank line.
