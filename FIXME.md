# Bugs/Issues

- Backtracking, that is, removing a installed rectangle from the heap may violate the invariants. Check the `split` method and fix this bug, since backtracking is useful for incorporation of further optmization schemes.

    - Though this issue does not affect basic usage, since greedy method needs no backtracking and delivers fair results
      already.
