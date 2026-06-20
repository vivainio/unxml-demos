# Gallery

Real-world XML documents rendered with [`unxml`](https://github.com/vivainio/unxml-rs), syntax-highlighted with the same grammar `unxml` ships for `bat`. Each link opens the full rendered output edge-to-edge.

The **Original** and **Rendered** columns compare the source XML against the `unxml` output (lines · bytes), so you can see how much the rendering compresses each document.

## XML documents

| Document | Original | Rendered | Source |
| --- | --- | --- | --- |
| [UBL — Invoice (instance)](xml/ubl/invoice-example.html) | 493 lines · 19.2 KB | 353 lines · 12.1 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xml/UBL-Invoice-2.1-Example.xml) |
| [UBL — Order (instance)](xml/ubl/order-example.html) | 341 lines · 13.6 KB | 250 lines · 7.5 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xml/UBL-Order-2.1-Example.xml) |
| [UBL — Credit Note (instance)](xml/ubl/creditnote-example.html) | 431 lines · 17.0 KB | 308 lines · 10.8 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xml/UBL-CreditNote-2.1-Example.xml) |

## Schemas

| Document | Original | Rendered | Source |
| --- | --- | --- | --- |
| [Finvoice 3.0](schemas/finvoice-3.0.html) | 1,690 lines · 95.1 KB | 1,123 lines · 45.3 KB | [source](https://file.finanssiala.fi/finvoice/Finvoice3.0.xsd) |
| [UBL — Core Component Types](schemas/ubl/cct.html) | 731 lines · 44.2 KB | 83 lines · 4.0 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xsd/common/CCTS_CCT_SchemaModule-2.1.xsd) |
| [UBL — Unqualified Data Types](schemas/ubl/udt.html) | 553 lines · 26.7 KB | 38 lines · 1.9 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xsd/common/UBL-UnqualifiedDataTypes-2.1.xsd) |
| [UBL — Qualified Data Types](schemas/ubl/qdt.html) | 69 lines · 3.5 KB | 5 lines · 424 B | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xsd/common/UBL-QualifiedDataTypes-2.1.xsd) |
| [UBL — Common Basic Components](schemas/ubl/cbc.html) | 5,388 lines · 214.7 KB | 1,752 lines · 90.0 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xsd/common/UBL-CommonBasicComponents-2.1.xsd) |
| [UBL — Common Aggregate Components](schemas/ubl/cac.html) | 39,798 lines · 2.3 MB | 5,401 lines · 288.4 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xsd/common/UBL-CommonAggregateComponents-2.1.xsd) |
| [UBL — Common Extension Components](schemas/ubl/cec.html) | 222 lines · 9.3 KB | 50 lines · 2.5 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xsd/common/UBL-CommonExtensionComponents-2.1.xsd) |
| [UBL — Invoice](schemas/ubl/invoice.html) | 1,001 lines · 58.8 KB | 120 lines · 6.1 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xsd/maindoc/UBL-Invoice-2.1.xsd) |

## XSLT

| Document | Original | Rendered | Source |
| --- | --- | --- | --- |
| [DocBook XSL — HTML driver](xslt/docbook/html-driver.html) | 558 lines · 20.0 KB | 338 lines · 10.2 KB | [source](https://cdn.docbook.org/release/xsl/current/html/docbook.xsl) |
| [DocBook XSL — inline elements](xslt/docbook/inline.html) | 1,598 lines · 49.8 KB | 826 lines · 21.4 KB | [source](https://cdn.docbook.org/release/xsl/current/html/inline.xsl) |
| [ISO Schematron — SVRL skeleton](xslt/schematron/iso-svrl.html) | 614 lines · 21.1 KB | 266 lines · 6.6 KB | [source](https://raw.githubusercontent.com/Schematron/schematron/master/trunk/schematron/code/iso_svrl_for_xslt1.xsl) |

## Schematron

| Document | Original | Rendered | Source |
| --- | --- | --- | --- |
| [EN16931 — UBL validation (driver)](schematron/en16931/ubl-validation.html) | 34 lines · 1.8 KB | 19 lines · 948 B | [source](https://raw.githubusercontent.com/ConnectingEurope/eInvoicing-EN16931/master/ubl/schematron/EN16931-UBL-validation.sch) |
| [EN16931 — abstract model rules](schematron/en16931/model.html) | 341 lines · 51.3 KB | 469 lines · 45.9 KB | [source](https://raw.githubusercontent.com/ConnectingEurope/eInvoicing-EN16931/master/ubl/schematron/abstract/EN16931-model.sch) |
| [EN16931 — UBL bindings](schematron/en16931/ubl-model.html) | 277 lines · 71.1 KB | 578 lines · 72.6 KB | [source](https://raw.githubusercontent.com/ConnectingEurope/eInvoicing-EN16931/master/ubl/schematron/UBL/EN16931-UBL-model.sch) |

