# Prerna website source code

Latest source of the Hindi Prerna self-help group website.

## Main files
- content/index.html: home page
- content/enquiry.html: enquiry form and local enquiry list
- content/daily.html: daily reporting form and local report list
- public/: retained image assets; the current home page displays no hero image
- app/: server routes, CSV downloads and printable pages

## Local development
Use Node.js 22.13+ and pnpm. Run `pnpm install`, then `pnpm dev`.
If the environment profile is requested, run the portable command below instead:
`pnpm exec vinext dev`

The current enquiry and daily report pages store records in the visitor browser. No submitted personal records, passwords or repository credentials are included in this archive. The legacy authenticated enquiries API needs a D1 binding and is not used by the current pages.

For hosting on Sites, create/select your own project and configure its hosting identity. The exported manifest intentionally omits the existing project ID. Retain the supplied server routes for CSV downloads and print pages.
