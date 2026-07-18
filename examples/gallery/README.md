# Vendored gallery sources

Larger real-world schemas/stylesheets rendered as full-page demos, vendored
here (instead of fetched at build time) so `scripts/generate-demos.py` can run
offline in CI against just a `pip install unxml` — no network fetch, no
dependency on a locally built `unxml-rs` binary.

Each subdirectory mirrors a `DEMOS` entry's slug in `scripts/generate-demos.py`.
Upstream provenance:

- `ubl/`, `cii/ubl-*` instance examples — [OASIS UBL 2.1](https://docs.oasis-open.org/ubl/os-UBL-2.1/) (OASIS Standard)
- `cii/` — [phax/en16931-cii2ubl](https://github.com/phax/en16931-cii2ubl) and
  [ZUGFeRD/mustangproject](https://github.com/ZUGFeRD/mustangproject) (MIT)
- `finvoice-3.0.xsd` — [Finanssiala ry Finvoice 3.0](https://www.finanssiala.fi/en/materials/finvoice-3-0/) (Finnish financial-industry invoicing standard)
- `docbook/` — [docbook/xslTNG](https://github.com/docbook/xslTNG) (MIT) and the
  classic [DocBook XSL stylesheets](https://cdn.docbook.org/release/xsl/current) (MIT)
- `schematron/` — [Schematron/schematron](https://github.com/Schematron/schematron) (MIT)
- `en16931/` — [ConnectingEurope/eInvoicing-EN16931](https://github.com/ConnectingEurope/eInvoicing-EN16931) (EUPL-1.2)
- `msbuild/` — [dotnet/msbuild](https://github.com/dotnet/msbuild) and
  [NuGet/NuGet.Client](https://github.com/NuGet/NuGet.Client) (MIT)

Re-vendor a file by re-fetching it from the URL noted next to its `DEMOS` entry
and overwriting the file in place — there's no fetch script anymore.
