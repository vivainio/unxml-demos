---
icon: lucide/home
---

# unxml demos

[`unxml`](https://github.com/vivainio/unxml-rs) turns verbose XML — schemas,
stylesheets, and rule sets — into a compact, indentation-based pseudocode that
is far easier to read, diff, and review than the angle-bracket original.

This site is a gallery of **real-world documents** rendered with `unxml`, so you
can judge the output on files you might actually have to read: UBL and Finvoice
schemas, DocBook XSL stylesheets, and EN16931 e-invoicing Schematron rules. Each
page is the full output, syntax-highlighted with the same grammar `unxml` ships
for [`bat`](https://github.com/sharkdp/bat).

[Browse the gallery :material-arrow-right:](demos/index.md){ .md-button .md-button--primary }

## What unxml does

`unxml` has a plain mode for any XML document, plus dedicated modes that rewrite
a specific vocabulary into idiomatic pseudocode. A few examples:

| Source | Rendered |
| --- | --- |
| `<xs:element name="Order" type="OrderType"/>` | `element Order : OrderType` |
| `<xsl:value-of select="$total"/>` | `<- $total` |
| `<assert test="cbc:EndpointID">…</assert>` | `assert cbc:EndpointID` |

The result is dramatically shorter — the gallery lists original vs rendered line
and byte counts for every demo (UBL's Common Aggregate Components, for instance,
drops from ~40,000 lines to ~5,400).

Each mode is documented with side-by-side samples:

- [XSD transformations](https://github.com/vivainio/unxml-rs/blob/main/docs/xsd.md) — `xs:*` / `xsd:*` schemas
- [XSLT transformations](https://github.com/vivainio/unxml-rs/blob/main/docs/xslt.md) — `xsl:*` stylesheets
- [Schematron transformations](https://github.com/vivainio/unxml-rs/blob/main/docs/schematron.md) — `.sch` rule schemas

## Get unxml

`unxml` is an open-source command-line tool written in Rust. Point it at any
XML, XSD, XSLT, or Schematron file:

``` bash
# pick the mode automatically from the file extension
unxml --auto some-file.xsd
```

See the [project README](https://github.com/vivainio/unxml-rs) for installation
(cargo, uv, or prebuilt binaries) and the full usage guide.
