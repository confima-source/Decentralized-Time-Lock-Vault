# Contributing

## Branch naming
- `feat/<short-description>` — new features
- `fix/<short-description>` — bug fixes
- `docs/<short-description>` — documentation only
- `chore/<short-description>` — maintenance / tooling

## Commit conventions
Follow [Conventional Commits](https://www.conventionalcommits.org/):
```
feat: add partial withdrawal support
fix: prevent re-entrancy on cancel_deposit
docs: update README fee section
chore: bump soroban-sdk to v23
```

## PR checklist
- [ ] `make check` passes (fmt + lint + test)
- [ ] New behaviour is covered by tests
- [ ] README updated if public API changed
- [ ] No secrets or private keys committed
