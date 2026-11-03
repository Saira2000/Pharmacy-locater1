Pharmacy Locator frontend export

This folder contains the production HTML, CSS, JavaScript, and supporting image and workbook assets.

Serve this folder as the website root so /assets/ and /favicon.png resolve correctly. Opening index.html directly from disk is not enough for map search or store-data uploads.

This is a frontend build, not a standalone app. The map search and Upload Updated Store Data feature require the matching Express API and database.

For development, apply the database schema with npm run db:push. Publish the full project to apply the production schema before using persistent uploads there. The editable application source remains in client/src, server/, and shared/.
