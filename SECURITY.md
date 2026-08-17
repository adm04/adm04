# Security Policy

## 🔒 Secret Management & Protection Guidelines

This repository follows strict security practices to ensure no sensitive credentials or personal data are exposed on GitHub.

### Rules for Managing Secrets & Credentials

1. **Never Hardcode Secrets**: 
   - Never commit API keys, access tokens, passwords, database URIs, or private keys directly into source code, workflow YAML files, or documentation.
2. **Use GitHub Actions Secrets**:
   - Store access tokens (such as `GH_PAT`) in repository secrets (`Settings` -> `Secrets and variables` -> `Actions`).
   - Workflows should reference secrets via `${{ secrets.SECRET_NAME }}`.
3. **Client-Side vs Server-Side Secrets**:
   - Environment variables exposed to client-side code (e.g., HTML/JS browsers) are **never secret**.
   - If an API requires a private key, route calls through a secure backend or serverless function.
4. **Environment Variables**:
   - Use `.env.example` as a public template with placeholder values.
   - Local `.env` files are ignored by git via `.gitignore`.

---

## 🛡️ Reporting a Vulnerability

If you discover a security vulnerability or exposed secret in this repository, please report it privately:

1. **Email:** Contact via GitHub No-Reply / Developer Dispatch.
2. **Do Not Open Public Issues:** Please refrain from creating public GitHub issues for security vulnerabilities.
