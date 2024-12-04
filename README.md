# Unexpected Behavior with Kotlin's `removeIf()` on Mutable Collections

This repository demonstrates a potential issue when using Kotlin's `removeIf()` function on mutable collections. While generally useful for filtering, `removeIf()` can lead to unexpected behavior under specific circumstances, particularly when combined with concurrent modifications or complex conditions.  The example illustrates the function's expected behavior and how it can produce unexpected results if not carefully handled.  The solution section proposes a safer approach using iteration for specific scenarios.

## How to run the code:

1. Clone this repository.
2. Open the project in your Kotlin IDE (e.g., IntelliJ IDEA).
3. Run the `bug.kt` file to see the unexpected behavior.
4. Run `bugSolution.kt` to see a safer alternative.