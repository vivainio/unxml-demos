# Vendored demo sources

Small, self-contained sample documents rendered into the gallery, kept in this
repo so the demo site doesn't depend on a third-party host for them. (Larger
real-world demos are still fetched on demand from their canonical upstream URLs;
see `demo/publish-to-demo-site.py` in the unxml-rs repo.)

## cii/

Minimal UN/CEFACT Cross Industry Invoice (CII) instance, from the MIT-licensed
[mustangproject](https://github.com/ZUGFeRD/mustangproject) test resources:

- `factur-x-basic.xml` — a Factur-X BASIC-profile invoice (`rsm:`/`ram:`/`udt:`
  prefixes, which `unxml --auto` recognises and hides)

## xslt/

Classic beginner XSLT stylesheets, adapted from the public
[W3Schools XSLT tutorial](https://www.w3schools.com/xml/xsl_intro.asp):

- `cdcatalog.xsl` — `for-each` + `value-of` building an HTML table
- `cdcatalog-choose.xsl` — `choose` / `when` / `otherwise`
- `cdcatalog-templates.xsl` — multiple `template`s driven by `apply-templates`
- `breakfast-menu.xsl` — the literal-result-element stylesheet form
