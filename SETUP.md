# GitHub Profile Setup

1. Create a new public repository with the exact same name as your GitHub username.

2. Copy these files into that repository:

   - `README.md`
   - `.github/workflows/metrics.yml`

3. Confirm the profile links and usernames:

   - GitHub: `Aarjav-333`
   - LeetCode: `okaarjav`
   - LinkedIn: `aarjav-oravakandi`

4. Add a GitHub secret named `METRICS_TOKEN`.

   Recommended token permissions:

   - `read:user`
   - `repo`, only if you want Metrics to analyze private repositories too

5. Go to the repository's Actions tab and run `Profile Metrics` manually once.

6. After the workflow finishes, the `metrics/*.svg` files will appear in your repository and your profile README will render them.

If any card fails, first check that the usernames and `METRICS_TOKEN` are correct.
