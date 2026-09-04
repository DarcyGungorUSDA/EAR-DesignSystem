# How much do you want to know?

## The basics
We're using **Arial** because it's available to us in both MS Office and Adobe without needing to download anything, and is similar to our website font. 

## Beyond the basics
In an ideal world, we'd use **source sans** for a consistent look and feel with the FNA website, which uses **source sans pro** (as of August 2026). Unfortunately, [even though **source sans** an Adobe font](https://fonts.adobe.com/fonts/source-sans), we don't have access to source sans regular in Adobe Acrobat:

<p align="center">
  <kbd><img width="214" height="203" alt="The source sans fonts available to FNA through Adobe Acrobat are source sans 3 black, extra bold, extra light, medium, and semi-bold." src="https://github.com/user-attachments/assets/3721844a-62fb-4762-9642-c4b0583ba7ea" /></kbd>
</p>

This puts us in a tight spot if we write a Word document in source sans pro, convert to pdf, and then need to edit a few words. It would be great to open the Acrobat text editor and just do it there - but, since we don't have source sans regular in Acrobat, the edited words would appear in a different font. It's a hassle to go back to the Word doc and re-convert to pdf for small edits every time.

And unfortunately, CEC can't provide an FNA-wide solution (... we tried in 2025 when developing the ~FNS~ FNA PowerPoint template). Each of us *could* logon to Adobe.com with our email address, add the source sans pro font family to our account, and edit the pdfs online - but it's a lot to assume everyone will do that.

So, the best option seems to be to pick a font that's available to us in MS Office and Adobe Acrobat without anyone needing to download anything. **Arial** fits the bill, and looks pretty similar to **source sans pro**:

<p align="center">
  <kbd><img width="800" height="auto" alt="Side-by-side comparison of source sans pro and arial using the phrase the quick brown fox jumps over the lazy dog." src="https://github.com/user-attachments/assets/3c6ac859-4c71-49f5-84aa-d381cebad1a6" /></kbd>
</p>

**Did we consider any other typefaces?**  
Yes:  
*Times New Roman*: This is a serif typeface (serifs = decorative hooks on the letters), which was designed for *print* not *screens*. Not only does it look outdated, the narrow letterforms that made it a good print choice (more words per line = less paper = lower cost!) also make it harder to read on a screen. Plus, [Section 508](https://www.section508.gov/develop/fonts-typography/) says to use sans-serif typefaces for body text that will be read on a screen - and that's how everyone interacts with our content now.  
*Calibri*: The (former) MS Office default. At one point, OCEE directed us to use calibri - but it kept triggering "character encoding" errors after converting to pdf: when a "t" and an "i" are side-by-side (like in the word "nutrition" - which we use a lot!) the two letters form a ligature, which means the cross of the "t" joins to the line of the "i," and the joined letters don't render correctly in pdf. It's fixable but, again, it's a lot to assume everyone will - it's simpler to pick a different font.  
*Public Sans, Roboto Mono, Merriweather*: These are the fonts the [U.S. Web Design System](https://designsystem.digital.gov/components/typography/#included-typefaces-2) recommends for government websites, in addition to sources sans pro. The only one we have access to in MS Office is Merriweather, but it's a serif typeface like  Times New Roman. If people love it we could use it for headings - but then it would look a little different from our website, which doesn't use Merriweather anywhere. 
*Verdana*: This typeface is an excellent alternative to Arial, and often promoted as a good choice for readers with dyslexia. I didn't pick it because the FNA PowerPoint templates uses Arial (Verdana takes up more space, which is limited on a slide). It's good to have a consistent typeface across all of our files. 
