# coq-style-guide
Rough musings about stylistic matters in Coq developments

## Rough Notes

Here are some notes, which should be cleaned up and nicely formatted later.

- When doing `repeat match goal with ... end`, have a separate step tactic that
  does it only once.  Easier to debug.
