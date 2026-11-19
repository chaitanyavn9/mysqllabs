# MySQL Database Lab

Ready-to-use GitHub Codespaces template for MySQL Database Lab.

## Start
1. Create a new GitHub repository.
2. Upload **all contents of this template folder** to the repository root, including the hidden `.devcontainer` folder.
3. Commit the files to `main`.
4. Open **Code → Codespaces → Create codespace on main**.
5. Wait for the first build, then run the sample below.

**Important:** `.devcontainer/devcontainer.json` must be directly inside the repository's `.devcontainer/` folder. Do not add an extra folder level.

## Is setup repeated?
No. The committed configuration is permanent for this repository. Reopening/restarting the same Codespace does not require setup again. A new Codespace created from this repository builds using the same configuration. Rebuild only after changing the configuration.

Stop unused Codespaces to avoid unnecessary compute usage. GitHub usage allowances and billing depend on the account/plan.

Start: `docker compose up -d`
Check: `docker compose ps`
Logs: `docker compose logs -f db`
Stop: `docker compose down`

Connection: host localhost, port 3306, database college_lab, user labuser, password labpass

Credentials are classroom-only examples. Never use them for production or sensitive data.
