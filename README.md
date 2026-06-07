# Slopper Community Lists

Community-maintained trust and risk lists for the [Slopper](https://github.com/Sloppers/Slopper) GitHub Action.

Every Slopper installation fetches these lists at runtime — no configuration needed.

## Files

| File | Purpose |
|------|---------|
| `risky_users.txt` | GitHub usernames flagged for AI slop / spam PRs |
| `trusted_orgs.txt` | GitHub orgs whose members get a score reduction |

## Contributing

- **Report a risky user**: Open an issue with links to evidence (spam PRs, AI slop patterns)
- **Add a trusted org**: Open a PR adding the org name to `trusted_orgs.txt`

All changes are reviewed before merging.
