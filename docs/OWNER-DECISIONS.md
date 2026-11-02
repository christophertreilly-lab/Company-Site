# Owner decisions (to-do list)

This file is in a public repository and is served by GitHub Pages like any other file. It contains only a list of open decisions, no private information.

## Content only the owner can supply
- [OWNER: confirm "Forensic Social Work Alliance" certificates wording]
- [OWNER: fees or retainer, and how a new matter is booked (email only, or an intake form)]
- [OWNER: confirm the proof behind the phrase "court accepted" (hero card and credentials panel)]
- [OWNER: exact wording of any disclaimers wanted, e.g. not for emergencies (911/988), contacting me does not create a client relationship, email is not secure]
- [OWNER: one line on what is NOT evaluated or is referred out, if wanted]
- [OWNER: a headshot you want to use, free of metadata]
- [OWNER: whether to add an intake path for families, and a privacy page]

## Settings outside the code
- In the repository Pages settings, confirm "Enforce HTTPS" is ticked.
- Submit https://chrisreillymsw.org/sitemap.xml in Google Search Console if you use it.

## Privacy review (2026-11-02)
- Checked the page and all files: no street address, no family details, no schedule or location hints, no analytics or trackers. The only outside requests are to Google Fonts (fonts.googleapis.com, fonts.gstatic.com). Optional: self-host the two fonts (Lora, DM Sans) so visitors' browsers never contact Google; not done here because it means adding font files.
- The photo had EXIF, XMP and Photoshop metadata blocks in the old page. The new image file (img/chris.jpg) was re-encoded and has none of them. The old page versions are still in the repository history, so the old embedded photo (with its metadata) can still be downloaded from history. Only deleting and recreating the repository removes that; this was not done.
- [OWNER: the repository history shows commits authored with a personal Gmail address. It is public in history. Options: leave it, or turn on "Keep my email addresses private" in GitHub account settings (affects future commits only). History was not rewritten.]
- New commits in this set use the author form christophertreilly-lab@users.noreply.github.com.
