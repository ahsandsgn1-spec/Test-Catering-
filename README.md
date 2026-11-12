# Test-Catering-
Practice landing page for learning Google Tag Manager, GA4 event tracking, and Meta Pixel setup.
Your landing page is ready: **index.html**. It's a demo catering site for offices and events, with a menu, an ordering section, a quote form, and WhatsApp and phone buttons for tracking practice.

**How to put it on GitHub**
1. Download `index.html`, then open it in a text editor (Notepad is fine) and copy everything.
2. In your repository, open `index.html`, click the **pencil icon**, select all the old text, and paste the new code.
3. Click **Commit changes** and wait 1-2 minutes. Refresh your live link, using incognito if the old page still shows.

If the repo has no `index.html` yet, use **Add file**, then **Create new file**, name it `index.html`, and paste the code.

**Before you publish, change these**
- Replace the phone number `923001234567` (it appears in the WhatsApp links and the call link) with your real number. Use the country code first, with no + or spaces.
- Find the two comments that say **PASTE YOUR GTM HEAD SNIPPET** and **PASTE YOUR GTM BODY SNIPPET**. Replace each comment with the matching GTM snippet.

**What you can track on this page**
- **WhatsApp clicks:** two links, with IDs `whatsapp-link` and `whatsapp-link-2`, both containing `wa.me`.
- **Phone clicks:** the link with ID `phone-link`.
- **Quote form submit:** the form pushes a custom event called `quote_form_submit` into the dataLayer. In GTM, create a **Custom Event** trigger with that exact name, and connect it to a GA4 event tag.
- **Button clicks:** `quote-link` and `submit-quote` have IDs for click triggers.

The footer says it's a demo site, so keep that line. It keeps your case study honest.

Once it's live, tell me when you reach the GTM triggers and I'll give you the exact settings for the WhatsApp click and the form event.
