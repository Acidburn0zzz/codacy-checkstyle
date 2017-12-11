Since Checkstyle 5.0

A check for detecting single lines that match a supplied regular expression. Works with any file type.

Rationale: This check can be used to prototype checks and to find common bad practice such as calling `ex.printStacktrace()`, `System.out.println()`, `System.exit()`, etc.