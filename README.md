# Dart Async Operation Error Handling

This repository demonstrates a common error and solution in handling exceptions within asynchronous operations in Dart.  The `bug.dart` file shows code that improperly handles exceptions by not re-throwing, leading to silent failures.  The corrected version, `bugSolution.dart`, shows the correct use of `rethrow` to propagate exceptions up the call stack for proper handling.