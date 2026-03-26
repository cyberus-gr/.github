# Contributing to Cyberus Projects

All contributions go through pull requests — **no direct pushes to `main`**.

## Process
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes with clear messages
4. Open a Pull Request against `main`
5. Wait for review from @mmcyberus or @ailinasopi

## Code Standards
- Python: follow PEP8, include docstrings
- All tools must be tested before PR submission
- No hardcoded credentials, tokens, or API keys — ever

## Security Tools Note
These repos contain offensive/defensive security tools.
Submissions must be for **research and educational purposes only**.
```

---

### 3. `CODEOWNERS` — Auto-assigns reviewers on every PR

Create `.github/CODEOWNERS` inside **each project repo** (not the `.github` repo itself):
```
# All files require review from both owners
* @mmcyberus @ailinasopi
