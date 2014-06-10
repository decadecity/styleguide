# Python

In general Python code follows PEP8: http://legacy.python.org/dev/peps/pep-0008/

(Much of what follows is taken from PEP8 to save me looking it up there.)

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

## Imports

Imports should be grouped in the following order with a blank line separating each section.

  1. standard library imports
  2. related third party imports
  3. local application/library specific imports

Imports should be in alphabetical order wherever practical.

## Whitespace

Avoid extraneous whitespace in the following situations:

Immediately inside parentheses, brackets or braces: `spam(ham[1], {eggs: 2})`

Immediately before a comma, semicolon, or colon: `if x == 4: print x, y; x, y = y, x`

Immediately before the open parenthesis that starts the argument list of a function call: `spam(1)`

Immediately before the open parenthesis that starts an indexing or slicing: `dict['key'] = list[index]`

Do not use more than one space around an assignment (or other) operator to align it with another:

    x = 1
    y = 2
    long_variable = 3

Don't use spaces around the `=` sign when used to indicate a keyword argument or a default parameter value:

    def complex(real, imag=0.0):
        return magic(r=real, i=imag)




