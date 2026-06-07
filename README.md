# Slopper Community Lists

Community-maintained trust and risk lists for the [Slopper](https://github.com/Sloppers/Slopper) GitHub Action.

Every Slopper installation fetches these lists at runtime — no configuration needed.

## Structure

```
risky_users/
  username1        # one file per reported user
  username2
trusted_orgs/
  kubernetes       # one file per trusted org
  apache
```

Each filename is the GitHub username or organization. File contents can include metadata (evidence links, notes) but only the filename matters.

## Contributing

- **Report a risky user**: Open an issue with links to evidence (spam PRs, AI slop patterns). The bot will create the file after validation.
- **Add a trusted org**: Open a PR adding a file to `trusted_orgs/` with the org name as filename.
- **Remove an entry**: Open a PR deleting the file.

No merge conflicts — each entry is its own file.
