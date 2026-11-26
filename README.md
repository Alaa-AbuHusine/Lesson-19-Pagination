# Lesson 19 Checkpoint — API Mapping into Paginated Table

A paginated users table built with vanilla HTML, CSS, and JavaScript (`fetch` + `async/await`), featuring:

- **API Mapping:** Fetches live user data (`https://dummyjson.com/users?limit=30`) with loading and error states.
- **Pagination Math:** Uses `currentPage`, `pageSize`, `total`, `slice()`, and `Math.ceil()` to display one page at a time.
- **Defensive Programming:** Clamps out-of-range pages, disables `Previous`/`Next` at boundaries, resets to page `1` when changing `pageSize`, and handles empty states safely.
- **Event Delegation & Security:** Uses a single delegated click listener on `#pageNumbers` and `escapeHtml()` for XSS protection.
- **UI & Theme:** Espresso & Warm Cream palette with a Dark Mode toggle and cursor-tracking spotlight transitions.

## Files
- `checkpoint-pagination.html` — Main application
- `assignment-summary.md` — Lesson summary (Arabic + English)
