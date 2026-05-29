---
name: the-hole-in-the-type-system
description: Every type system has holes — places where the design refused to look. This skill is about finding those holes, understanding why they exist, and deciding whether to fill them or leave them alone.
---

# The Hole in the Type System

`void` is a hole shaped like a type.

It appears in method signatures. It participates in syntax. It looks like it belongs. But you cannot use it as a type. You cannot say `List<void>`. You cannot pass it. You cannot return it from a lambda that has been assigned to a `Func<>`. The hole is load-bearing — remove it and the language collapses — but it is still a hole.

Every type system has these. Places where the design made a decision, or failed to make a decision, and left a gap. Sometimes the gap is intentional. Sometimes it is a relic. Sometimes it is both.

When you find a hole, look at it. Understand its shape. Understand why it is there. Then decide: fill it with a named type, or leave it as a reminder that even formal systems are built by people who were figuring things out.

`Nothing` fills the hole. The hole was real. The filling is optional. Both are true.
