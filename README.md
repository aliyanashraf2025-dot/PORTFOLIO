# Muhammad Aliyan — portfolio site

One file: `index.html`. No build step, no backend.

## 1. Your details
Email, WhatsApp, Instagram and both graded portraits are already built in. To change anything later:
Open `index.html` in any text editor, search for `const CONFIG`, and fill in:

- `email` — your email
- `whatsapp` — country code + number, digits only (e.g. `923001234567`)
- `instagram`, `youtube`, `tiktok`, `behance`, `vimeo`, `linkedin` — full links (leave `""` to hide)
- `showreel` — any YouTube or Vimeo link
- `photo` — leave empty to keep the graded portrait that's built in
- `web3formsKey` — optional, see step 3

## 2. Deploy to Vercel
**Option A (no install):** create a GitHub repo, upload this folder's files, then on vercel.com click Add New → Project → import the repo → Deploy. Framework preset: "Other". No build command.

**Option B (terminal):** in this folder run `npx vercel` and follow the prompts, then `npx vercel --prod`.

## 3. Make the contact form email you directly (free)
Get a free access key at web3forms.com (enter your email, the key is emailed to you) and paste it into `web3formsKey`. Without a key the form still works: it opens the visitor's email app with the message ready to send.
