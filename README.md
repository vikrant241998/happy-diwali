# Diwali.exe — GitHub + Netlify Auto Deploy 🪔

**Created for Vikrant Mulankar.** This is the complete static website.
No paid API, npm, build command, or dependencies required.

## One-time setup using phone

1. Log into GitHub on your mobile browser. Create a repository named `diwali-dev-edition` (you can keep it private).
2. Put the **files inside this folder** (`index.html`, `og-preview.png`, `netlify.toml`, `.gitignore`) in the ROOT of your GitHub repository. Do not upload the .zip as a single file.
3. Log into your own Netlify account through https://app.netlify.com/.
4. Choose **Add new project → Import an existing project → GitHub**.
5. Approve Netlify's official GitHub authorization, select `diwali-dev-edition` and branch `main`.
6. **Build command: leave blank**. **Publish directory: `.` (project root)**. Deploy.
7. Netlify shows your real `https://...netlify.app` URL. Verify that the site is **public**, if you plan to share it.
8. To enable a reliable rich WhatsApp preview, replace the relative `og:image` URL in `index.html` with `https://YOUR-REAL-SITE.netlify.app/og-preview.png`, commit the change, and let Netlify redeploy.

## After setup

GitHub commit/push to `main` → Netlify deploys updated site automatically. You do NOT need to re-upload the folder. If you connect a GitHub write-capable plugin to ChatGPT and authorize changes, ChatGPT may be able to commit requested code updates to your repo. Write access and user approval depend on integration settings. Without that access, changes cannot be published automatically from chat.

## Personalize

Open `https://YOUR-REAL-SITE.netlify.app/?to=Rahul` to prefill a name.

## Security

Never paste password, OTP, session cookie, or personal access token in ChatGPT. Use GitHub/Netlify official OAuth authorization screens.
