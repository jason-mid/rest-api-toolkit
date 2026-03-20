## REST API Naming Conventions Best Practices

- **Use nouns, not verbs** to represent resources. Collections use plural nouns (e.g., `/users`), single items use singular nouns with an identifier (e.g., `/users/{id}`).
- **Consistent hierarchy**: Use forward slashes (`/`) to indicate hierarchical relationships (`/customers/{customerId}/accounts`).
- **Plural for collections and stores**, singular for document resources.
- **Lowercase and hyphens**: Use lowercase letters and hyphens (`-`) for readability; avoid underscores and trailing slashes.
- **No file extensions** in URIs.
- **Avoid CRUD action names** in paths; rely on HTTP methods (GET, POST, PUT, DELETE).
- **Use query parameters** for filtering, sorting, pagination rather than creating new endpoints.
- **Do not use verbs** in URIs; treat actions as resources when necessary.

These guidelines help create intuitive, maintainable, and standards‑compliant REST APIs.