# Obverse Playground — built site

This repo holds the **built static site** for the Obverse Playground — a
fully client-side web REPL for [Obverse], a Verse-inspired functional logic
language (unification, ordered choice, dataflow concurrency, and a real
finite-domain constraint solver, over plain JSON values).

**Run it: https://bakkemo.github.io/obverse-playground/**

Everything runs in your browser — programs execute in a Web Worker against
the real language kernel; there is no server, no accounts, no analytics,
and no network requests at runtime.

This is a deploy artifact: the playground is developed elsewhere and every
deploy is gated on a content oracle — a test suite that executes every
example, reference snippet, and tutorial exercise against the kernel and
pins their answers — so the published site cannot ship a program that does
not run.

[Obverse]: https://bakkemo.github.io/obverse-playground/
