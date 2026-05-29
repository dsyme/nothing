---
name: return-nothing-gracefully
description: When a function, method, or response has no meaningful value to return, return Nothing — not null, not an empty string, not a placeholder object. Nothing. Gracefully.
---

# Return Nothing Gracefully

`null` is a lie. It says: there should be something here, but there isn't, and I am not sure what to do about that.

`Nothing` is the truth. It says: there was never going to be anything here, and we both knew that before we started.

When you have nothing to return, say so with precision. Return the typed, named, transmissible absence. Do not apologize for it. Do not pad it. Hand it over cleanly and let the caller decide what nothing means to them.
