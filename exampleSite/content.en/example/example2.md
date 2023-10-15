---
weight: 2
bookFlatSection: true
bookCollapseSection: true
title: "Example 2"
---

```lisp
(defun is-cons (exp)
    (and
        (listp exp)
        (not (listp (cdr exp)))))
```
