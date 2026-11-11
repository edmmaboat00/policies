# Privacy policies

One place for the privacy policies of my browser extensions, published with GitHub Pages:

**https://edmmaboat00.github.io/policies/**

Each extension has its own folder, and its policy lives at `https://edmmaboat00.github.io/policies/<folder>/`.
Use that address in the Chrome Web Store, Microsoft Edge Add-ons and addons.mozilla.org listings.

| Extension | Policy address |
|---|---|
| Text to Speech – Read Aloud | https://edmmaboat00.github.io/policies/text-to-speech-read-aloud/ |
| YouTube Video Toolkit | https://edmmaboat00.github.io/policies/youtube-video-toolkit/ |
| Note Pro | https://edmmaboat00.github.io/policies/note-pro/ |
| WhatsApp CRM Pro | https://edmmaboat00.github.io/policies/whatsapp-crm-pro/ |
| Salary Calculator | https://edmmaboat00.github.io/policies/salary-calculator/ |
| GPhotos Sweeper | https://edmmaboat00.github.io/policies/gphotos-sweeper/ |

The last five were copied unchanged from their original single-policy repos (`youtube-video-toolkit` from
YouTube-ToolKit-Policy, `note-pro` from note-pro-privacy, `whatsapp-crm-pro` from whatsapp-crm-pro-privacy,
`salary-calculator` from saraly-calculator-privacy, `gphotos-sweeper` from gphotos-sweeper-privacy). Those old
repos still work and existing store listings still link to them; switch the listings here when convenient.

## Adding a policy

1. Copy an existing folder (for example `text-to-speech-read-aloud`) and rename it, using lowercase words and
   hyphens: `my-new-extension`.
2. Edit its `index.html`: the `<title>`, the heading, the "Last updated" date and the text.
3. Add a line for it to the list in the top-level `index.html` and to the table above.
4. Commit and push:

   ```
   git add -A
   git commit -m "Add My New Extension privacy policy"
   git push
   ```

GitHub Pages publishes the change within a minute or two.

`.nojekyll` tells GitHub Pages to serve the files exactly as they are.
