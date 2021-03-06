Python provides several useful methods that can be used to manipulate strings.
These methods can be used for cleaning, splitting, translating, or otherwise working with any object of type `str`.
Strings can be concatenated using the `+` operator or with `str.join()`.
Strings also implement all common sequence operations and can be iterated through using the `for item in <string>` syntax.

Strings are immutable, meaning the value of a `str` object in memory cannot change.
That means any functions or methods that operate on a `str` object will return a _new instance_ or copy of that `str`, instead of modifying the original.
