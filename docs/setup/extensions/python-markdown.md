# Python Markdown

Material for MkDocs supports a large number of [Python Markdown] extensions,
which is part of what makes it so attractive for technical writing. Following
is a list of all supported extensions, linking to the relevant sections of the
reference for which features they need to be enabled.

  [Python Markdown]: https://python-markdown.github.io/

## Supported extensions

### Abbreviations


The [Abbreviations] extension adds the ability to add a small tooltip to an
element, by wrapping it with an `abbr` tag. Only plain text (no markup) is
supported. Enable it via `mkdocs.yml`:

``` yaml
markdown_extensions:
  - abbr
```

No configuration options are available. See reference for usage:

- [Adding abbreviations]
- [Adding a glossary]

  [Abbreviations]: https://python-markdown.github.io/extensions/abbreviations/
  [Adding abbreviations]: ../../reference/tooltips.md#adding-abbreviations
  [Adding a glossary]: ../../reference/tooltips.md#adding-a-glossary

### Admonition

The [Admonition] extension adds support for admonitions, more commonly known as
_call-outs_, which can be defined in Markdown by using a simple syntax. Enable
it via `mkdocs.yml`:
