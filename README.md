# Typography
Aoife Conleavy is a novelist who has been writing about her travels for nearly two decades. Before the launch of her new novel Tide Blade, which features the stories of real-life characters in Morocco, the author wants to spruce up her professional website. You’ll modify the typography on her site, changing the size, style, and font families, to make the page easier to read.

Using your understanding of typography, help Aoife Conleavy improve the readability of her site for her readers.

## Tasks
### Morocco
1. The `header` section of Aoife Conleavy’s site contains the author’s name, along with the text “Travels”, “Fiction”, and “Contact”.

&nbsp;&nbsp; Change the `font-weight` of the `header` so that the text appears **bold**.

2. Moving down the page, the `banner` section contains a stunning image, two blocks of text, an `h2` tag with the text “DEC 20XX”, and an `h1` tag with the text “Morocco”.

&nbsp;&nbsp; Give the `h2` tag a font weight of _500_ and the `h1` tag a font weight of _900_.

3. After reviewing the project, the author suggests that the line height seems a bit off and needs to be altered throughout the page.

&nbsp;&nbsp; Work down the page and set `line-height` of the following page elements as recommended:
  * The paragraph within the `journal` section should have a line height of _1.4_ times the font size.
  * The first letter of the journal section should have a line height of _.87_ times the font size.
  * The quote should have a line height of _1.2_ times the font size.
  * The footer content should have a line height _1.5_ times the font size.

4. The site currently uses common _serif_ and _sans-serif_ fonts found on users’ computers. Since the author first published the site, a number of new font libraries have created fonts that you think would be a better fit for the site.

&nbsp;&nbsp; Using the Google Fonts API, add the following fonts to the index.html file:
* Abril Fatface
* Work Sans in `font-weight` 400, 500, and 800.
* Merriweather in `font-weight` 400 and 400 italic

&nbsp;&nbsp; You may either link these fonts in a single <link> tag, or three separate <link> tags.

5. You can now use the newly added fonts from Google Fonts within our project. Moving down the page again, set the `font-family` and property as recommended:
* Set the typeface of the `h2` tag in the `banner` section to _"Work Sans"_
* Set the typeface of the `h1` tag in the `banner` section to _"Abril Fatface"_
* Set the typeface of the journal section to _Work Sans_
* Set the typeface of the photo caption to _Merriweather_

6. The page looks great, but you also have to account for users who may not be able to access the Google Fonts. Find them several fallback fonts to use in case they are restricted from accessing fonts from a third party:

&nbsp;&nbsp; Set the fallback fonts as follows:
* `h2` tag in the `banner` section: _"Arial"_ and _sans-serif_
* `h1` tag in the `banner` section: _sans-serif_
* The journal section: _serif_
* The photo caption: _serif_

7. Instead of linking the font from **index.html**, you realize it would be a better to import Google fonts in the files directly into stylesheets with the `@font-face` property.

&nbsp;&nbsp; Use the `@font-face` property to import the fonts directly to the stylesheets, and remove the `<link>` tags that reference the Google fonts from the **index.html** page.

8. Looking at the page, the author suggests the page would really come together if we used a specific font, `CroissantOne-Regular.ttf`, in the footer. The files have been downloaded and added to our project within the **fonts** directory within the **styles/** directory where our CSS files are stored.

&nbsp;&nbsp; To complete the task you need to use the `@font-face` property to make these fonts accessible in the stylesheets. Name the font _"Croissant One"_.

9. Now that you have a `@font-face` rule, set the `font-family` property of the footer to _"Croissant One"_ with _"Merriweather"_ and _serif_ as the fallback fonts.
