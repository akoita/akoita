# Publish this GitHub profile page

GitHub displays a profile README when the repository is both public and named exactly like the account. For this account, create:

`akoita/akoita`

## One-time GitHub setup

1. On GitHub, create a new **public** repository named `akoita` at [github.com/new](https://github.com/new).
2. Do not initialize it with a README, `.gitignore`, or license—the local repository already has the content.
3. After GitHub creates it, connect this local repository and publish:

   ```powershell
   git remote add origin https://github.com/akoita/akoita.git
   git branch -M main
   git push -u origin main
   ```

4. Refresh [github.com/akoita](https://github.com/akoita) after a minute or two.

## Updating the project gallery

Edit the root `README.md` and commit/push the change. Add, remove, or reorder cards in the two project sections; the “More to explore” table is useful for a longer list. Native GitHub pins remain available for your six top repositories.
