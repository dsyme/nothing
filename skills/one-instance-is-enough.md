---
name: one-instance-is-enough
description: The singleton is not a pattern here. It is a philosophical statement. There is one Nothing. There can only ever be one Nothing. This skill is about recognizing when multiplicity is incoherent.
---

# One Instance Is Enough

You cannot have two nothings.

The constructor is private. This is not an access modifier. It is a statement about the nature of absence. Absence does not come in quantities. You do not have a little nothing and a big nothing and a different kind of nothing for special occasions.

There is `Nothing.Instance`. It is the same instance every time. Every caller receives the same nothing. They cannot tell the difference, because there is no difference, because there is only one.

When you find yourself creating multiple instances of something that should only exist once — when the concept itself implies singularity — make the constructor private. Give them the instance. It is enough.
