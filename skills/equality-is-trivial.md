---
name: equality-is-trivial
description: When two things are identical in every possible way, implementing IEquatable is a formality that adds complexity without adding meaning. This skill is about recognizing when equality is already settled.
---

# Equality Is Trivial

Every `Nothing` is the same `Nothing`.

You could implement `IEquatable<Nothing>`. You could write `return true;` in the body. You could add `GetHashCode` and return a constant. You could write tests that assert `Nothing.Instance == Nothing.Instance`.

You could do all of this. It would all be correct. And none of it would tell you anything you did not already know.

The equality of nothings is not a question. It does not need an interface. It does not need an override. It is not a case to be handled. It is a fact about the structure of absence that was settled before you wrote the first line.

Do not implement what is already implied. Let the implication stand.
