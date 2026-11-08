# Sheet Audit Trail — demo

Sample repo for [RyMB-007/sheet-audit-trail](https://github.com/RyMB-007/sheet-audit-trail).

`models/valuation.xlsx` is a small DCF model. Every pull request that changes a
workbook gets an audit comment from `.github/workflows/spreadsheet-audit.yml`.

See the open pull request for an example: it inserts a Capex row, overwrites the
WACC formula with a hardcoded number, enters revenue growth as `8` instead of `8%`,
and breaks the EBITDA formula pattern in one year.
