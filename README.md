## Assessment for Helthy

You will do some peer evaluation. Every group will evaluate one other group using the checklist below.    

## Doing the evaluation
1. Create a file in this folder
2. Copy the requirements below into it
3. Tick the right boxes
4. Commit/push the change

## Requirements

### Perfection is not a detail
- [x] All buttons and links work
- [x] All elements work and are complete (menu, lists, images, ...)
- [x] Everything on the page has a function, a reason to be there -> Maybe delete the home button if you use the logo to go back to home
- [x] No dead links
- [x] English and dutch are not mixed
- [ ] No spelling errors  -> *Check out (https://languagetool.org/nl), there are some spelling errors*
- [ ] No grammar errors -> *Check out (https://languagetool.org/nl), there are some grammar errors*
- [x] The website is deployed somewhere -> It is deployed, but it gives a 404 page
- [x] Everything is relevant (no image of a barber on the website of a baker)

### Content
- [x] Openinghours (if needed)
- [x] Address (if needed)
- [x] Clickable email

### Text life matters aka typography is real
- [x] Some words have a different color
- [x] We aren't using a default font, cause it's not 2004
- [x] Contrast is not too low
- [x] Typographic hierachy is correct
- [x] Text has a clear intro, middle, conclusion
- [x] Intro, middle, conclusion is style correctly

### Style
- [x] Black is almost black but not #000
- [x] White is almost white but not #fff
- [x] The styling is consistent
- [x] It is not four totally different pages thrown together
- [x] Everything works even if you are colorblind

### Not everyone has free 4G aka speed matters
- [x] Pictures are not too heavy
- [x] Pictures are not pixelated

### A company wants to be found/SEO	
- [x] All the keywords this company wants to be found on are on the page 
- [x] Page has an H1 tag
- [x] Page has keyword meta tags
- [ ] Page has a title with the keywords in -> *We didn't find a title with one of the keywords in it*
- [x] Page loads fast
 
### Keep your workspace clean
- [x] No unused files in the repo
- [x] All files have a good, clear name -> In the recipes folder, you could change the names a bit, but overall it looks good
- [x] Good folder structure
- [x] The CSS folder does not have an image folder
- [x] Not too many files in the root folder 

### Git(hub) is what you make it
- [x] All commits use a good comment
- [x] A github description has been filled in
- [x] A github website has been filled in

### Readme but also writeme
- [x] The readme says who made it
- [x] The readme says why they made it
- [x] The readme explains what this repo/project is
- [ ] The readme links to a preview (screenshot)
- [ ] The readme contains a nice image
- [x] The readme has a markdown title
- [x] The readme is divided in sections
- [x] The readme is fun to read
- [x] The readme looks good
- [x] The readme is clear, even for someone that has no idea what is going on

### I'm So Meta, Even This Acronym
- [x] Keywords meta tag
- [x] Description meta tag
- [x] Title of the page is included
- [x] Favicon is included
- [x] Responsive meta tag is included
- [x] Charset is defined
- [x] Author is defined

### Perform all the tests
- [ ] Lighthouse -> *couldn't do this local*
- [ ] W3C validator -> *2 errors in the contact page*

### Putting the antics back in semantics (but only for the html)
- [x] The html is semanticly correct
- [x] Navigation is in a nav
- [x] Lists use list tags
- [x] H tags are used to signal importance
- [x] No div is used where another element is available
- [ ] No span is used where another element is available -> *there is a span tag where we think you can use an em tag*
- [ ] No inline styling is put on any element ->  *inline styling in the iframe, or should it be like this..?*
- [x] Id's are only used once
- [x] The same 'type' of elements have the same classes
- [ ] All images have an alt attribute and a title -> *there are some images that still need an alt tag*

### Just kidding CSS deserves some love too
- [x] CSS follows the DRY principle
- [x] The CSS does not contain conflicting selectors (multiple definition for the same class/id)
- [ ] There is no use of !important where it can be avoided -> *on rule 217 in styles.css*
- [x] The page is responsive

### Thermometer goes WHERE???
- [x] Your own style is included after the style of frameworks
- [ ] Script tags are put at the end of the body or in the head with async/defer if possible -> *not yet*

### Errors are to be avoided
- [x] No http resources are used on an https website
- [ ] The console shows no errors -> *workshops.html missing associated label*
