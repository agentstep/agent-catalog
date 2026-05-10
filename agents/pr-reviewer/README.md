# PR Reviewer — managed-agent template

Reviews pull requests for bugs, style violations, security issues, and test coverage gaps. Posts inline fix suggestions directly on the PR.

## What it does

1. Fetches the PR diff and file list from the repository
2. Analyzes each changed file for correctness, style consistency, and potential bugs
3. Checks for common security anti-patterns (SQL injection, XSS, hardcoded secrets)
4. Identifies missing test coverage for new or changed logic paths
5. Posts inline comments with specific fix suggestions and severity ratings
6. Produces a summary comment with an overall assessment and blocking vs. non-blocking issues
