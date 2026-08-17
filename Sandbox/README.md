# Sandbox (local experiments)

**Local only — not in git.** Throwaway maps, assets, and scripts. Keep this folder off `Content/` so it is not cooked.

## Do not

- Reference `Sandbox/**` from plugin `Source/` or `Content/`
- Commit sandbox files (gitignore blocks them except this README)

## Gitignore

| Path | In git? |
|------|---------|
| `Sandbox/*` | No |
| `Sandbox/README.md` | **Yes** |
