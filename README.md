# Resume Tailor — Privacy Policy

The public privacy policy for the **Resume Tailor** Chrome extension, ready to host for free on
**GitHub Pages**. The policy is a single self-contained file, [`index.html`](index.html) — no build
step, no Jekyll, no dependencies.

## Before you publish — fill in the placeholder

Open [`index.html`](index.html) and replace the one remaining placeholder:

- `[BUSINESS MAILING ADDRESS]` — your business mailing address (a Chrome Web Store "trader"
  requirement). Search the file for `[BUSINESS MAILING ADDRESS]`.

Everything else is already set: operator **Mosi**, contact **resumetailor@mosireserve.com**,
effective date **June 20, 2026**.

> **Note on data retention:** Section 6 states a default retention/deletion timeline (active data
> removed within 30 days of a deletion request, backups within 90 days). Adjust those numbers if
> your actual practice differs.

## Host it on GitHub Pages (free)

1. Create a new **public** repository on GitHub (e.g. `resume-tailor-privacy-policy`).
2. Push this folder to it:
   ```bash
   git remote add origin https://github.com/<your-username>/resume-tailor-privacy-policy.git
   git branch -M main
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** = *Deploy from a branch*, **Branch** = `main`,
   folder = `/ (root)`, then **Save**.
5. Wait ~1 minute. Your policy will be live at:
   ```
   https://<your-username>.github.io/resume-tailor-privacy-policy/
   ```

That HTTPS URL is what you paste into:

1. **Chrome Web Store dashboard → Privacy policy URL**, and
2. (recommended) a link from the extension's in-app **Settings** page.

## Keep the Chrome Web Store "Privacy practices" tab consistent

The store listing's data-collection answers must match this policy:

- **Collects:** personally identifiable information (name/contact from the resume, optional email)
  and user-supplied job postings.
- **Used only** to provide the resume-tailoring functionality.
- **Not sold** to third parties.
- **Encrypted in transit and at rest.**

## Editing later

Just edit the text in [`index.html`](index.html) and push. When you make a material change, update
the **"Last updated"** date near the top of the file.

---

`PRIVACY_POLICY_HANDOFF.md` is an internal brief and is excluded from git via `.gitignore` so it is
not published to the public repo.
