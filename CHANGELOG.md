## v Next ()

## 1.1.0 - Removed deprecated selectors (2018-11-07)
  * Thanks to [@UserFA15](https://github.com/UserFA15), this theme is now compliant with modern versions of Atom (removed deprecated selectors).

## 1.0.0 - Fixes and 1.0 (2016-08-07)
  * Fixes annoying bug where the current line would hop a few pixels.  Thank you for the PR, [@SrTobi](https://github.com/SrTobi) !!!
  * Calling this v1.0 - I think it's pretty much done.  :-)

## 0.2.18 - Fix (2016-03-23)
  * Markdown changes!!!
    * URLs are now blue.
    * The linked text is now bolded including the square brackets.
    * GitHub "@" Mentions are now bold and rusty-red.
    * GitHub issue numbers are now bold and rusty-red.
    * In the Markdown preview pane, text defaults to black and links are underlined and in blue.

## 0.2.16 - Fix (2015-09-15)
  * Fixed horrible white-on-red syntax highlighting for "invalid.illegal" strings - aka unterminated string constants.  Now will just show the remainder of the file as one big string like most editors do.

## 0.2.15 - Fix (2015-08-11)
  * "Other" keywords in TypeScript are now blue (`export`, for example).

## 0.2.12 - Fixes (2015-07-13)
  * Lightened color of indent-guide.

## 0.2.3 - Fixes (2015-06-30)
  * Markdown headers, unordered list bullets, and quote bullets are now rendered in bold with a teal color.  Quoted text in Markdown is now rendered in a dark gray.  This is an improvement on the default VS rendering which currently has no colorization at all.

## 0.2.2 - Fixes (2015-06-30)
  * Fix for colorization of indent guides (vertical lines).  The color implemented here is lighter than the official VS color.

## 0.2.1 - Fixes (2015-06-28)
  * Fix for colorization on general Function type declaration (This is an improvement on how VS does it).
  * Fix for colorization on if/else, return, and arrow functions in TS.

## 0.2.0 - Fixes (2015-06-28)
  * Fix for colorization of embedded expressions in ES6 template strings.
  * Fix for namespace keyword appearing black in C#.
  * Fix for operators (such as +) in TypeScript appearing blue.

## 0.1.0 - First Release (2015-06-28)
  * Decent support for TypeScript and CSS.  Basic support for C#.
