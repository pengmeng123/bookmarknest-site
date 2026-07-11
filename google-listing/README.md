# Chrome Web Store Listing

## URLs

- Website: `https://pengmeng123.github.io/bookmarknest-site/`
- Privacy policy: `https://pengmeng123.github.io/bookmarknest-site/privacy.html`
- Support: `https://pengmeng123.github.io/bookmarknest-site/support.html`

## Store name

BookmarkNest: X Bookmark Manager

## Short description

Search, organize, export, and protect X bookmarks in a local-first research library.

## Full description

BookmarkNest turns X and Twitter bookmarks into a local-first research library. Import bookmarks using your existing signed-in X session, then search posts by text, author, handle, folder, tag, and note. Organize your library with folders, tags, archive, saved views, and local automation rules. Export your work to JSON, Markdown, or CSV.

Bookmark content stays in your browser by default. Optional encrypted Cloud Sync creates a protected backup for device changes and restores. The extension encrypts backup data before upload; plaintext bookmark content is not sent to the Cloud Sync service.

Free includes local search, folders, tags, archive, delete, and JSON backup. Pro unlocks research notes, saved views, Markdown and CSV export, bulk actions, background sync, mirror removals, and encrypted Cloud Sync.

Pricing before taxes: Monthly Pro $2.99/month, Annual Pro $24.99/year, or Lifetime Pro for a one-time $49 purchase. Lifetime Pro covers the Pro features available while BookmarkNest is available. Cloud Sync retains up to five backup versions and may throttle changed backups to one per minute.

## Permission justification

- `storage`: stores settings and license status locally.
- `downloads`: saves user-requested exports and backups.
- `clipboardWrite`: copies original X post links.
- `webRequest`, `declarativeNetRequest`, `declarativeNetRequestWithHostAccess`, `cookies`, and X host access: enable authenticated bookmark imports through the user's existing signed-in X session.
- `alarms`: supports optional background auto-sync.

BookmarkNest does not request `<all_urls>`, `activeTab`, or `scripting`.

## Upload checklist

- Add 128x128 store icon and 16/32/48/128 extension icons.
- Add at least one clear product screenshot and one Cloud Sync screenshot.
- Link the public privacy policy and support pages above.
- Verify the text matches the released extension permissions and pricing.
