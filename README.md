# Unexpected Behavior of removeIf on Kotlin Maps

This repository demonstrates a subtle but important difference in how `removeIf` works with different Kotlin collection types (Lists, Sets, and Maps).

The `bug.kt` file shows the unexpected behavior when using `removeIf` on a mutable map. While `removeIf` works as expected with Lists and Sets, it produces unexpected results when used on the `entries` of a mutable map.  The solution, provided in `bugSolution.kt`, shows how to correctly remove elements from a map based on their value.

This example highlights the importance of understanding the underlying mechanisms of Kotlin's collection operations to avoid unexpected behavior in your code.