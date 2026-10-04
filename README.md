# Complementary Medicine Consultants – website

A plain HTML/CSS site. There is no WordPress, database, or monthly software fee, so it can be hosted for free.

## What's in here
| File | Page |
|---|---|
| index.html | Home |
| about.html | About |
| chiropractic.html | Chiropractic |
| acupuncture.html | Acupuncture |
| first-visit.html | Your First Visit |
| forms.html | Patient Forms |
| contact.html | Contact (phone, address, Google map) |
| css/style.css | All colors, fonts, and layout. The colors are at the top of the file. |
| images/ | Original illustrations (SVG). Free to use, with no licensing. |
| forms/ | Put downloadable PDF forms here. |

## Before you cancel the old service
1. **Find out who holds the domain** (complementarymedicineconsultants.com). If the current web company registered it, ask them to transfer it to your mom's own registrar account (Cloudflare, Namecheap, Porkbun, etc.) first. Don't cancel until the transfer is complete, or you could lose the domain.
2. **Check her email.** If her email uses that domain and runs through the same company, move it before canceling (Google Workspace, Zoho, etc.).
3. Download anything else from the old site you want to keep.

## Free hosting options
**GitHub Pages:** create a repo, upload these files to the root, and go to Settings → Pages → Deploy from branch `main`. Add the custom domain under Settings → Pages, then set the DNS records GitHub lists.

**Netlify or Cloudflare Pages:** drag the whole folder onto the dashboard, then connect the domain.

Both options give you free HTTPS.

## Common edits
- **Text:** open the .html file in any text editor and change the words between the tags. The header and footer are repeated on every page, so a change to the phone number or address needs to be made in all 7 files (find-and-replace works).
- **Swap an illustration for a real photo:** put `office.jpg` in `images/` and change `src="images/balance.svg"` to `src="images/office.jpg"`. Photos about 1200px wide work well.
- **Add a patient form PDF:** put it in `forms/` (for example `forms/new-patient-intake.pdf`). In forms.html, remove the `<!--` and `-->` around the example list item and update the file name.
