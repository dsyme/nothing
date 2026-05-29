---
name: the-compiler-already-knows
description: Some things do not need to be tested. Some things do not need to be checked. The compiler has already verified them. This skill is about recognizing what is already proven and leaving it alone.
---

# The Compiler Already Knows

The test for `Nothing` is: it compiles.

If it compiles, `Nothing.Instance` exists. It is not null. It is the correct type. It has the correct methods. The constructor ran. The static initializer completed. The field was assigned.

You do not need to write a test for this. The type system is the test. The compiler is the assertion. Every build is a passing test suite for the things the compiler can verify.

Write tests for behaviour that cannot be proven at compile time. Leave the rest to the machine that was built for exactly this purpose. Do not duplicate its work. Do not distrust it without cause.

Some knowledge is already certain. Treat it as such.
