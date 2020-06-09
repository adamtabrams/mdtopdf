# About

The mdtopdf tool takes your markdown files and converts them into a
PDF document. To do this it actually uses groff as an intermediate format.
Groff has been around for a long time and has a superset of markdown's
features.

### The current implementation is a proof of concept.

# Usage

You can test out the current capabilities by running:
```
./mdtopdf tests/basic.md basic.pdf
```
