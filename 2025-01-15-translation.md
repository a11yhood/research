# translation notes

collections of links at the intersection of translation and accessibility.

## TLDR

* `aria-label` still stinks, use `aria-labelledby` or you're in for a world of hurt. same goes for `aria-description` which uses the [accName heuristics](https://www.w3.org/TR/accname-1.2/).
* translation will cause text problems spacing and display inaccessibilities if not handled correctly
  * [<ruby><code>a11y.css</code><rt>alix</rt></ruby>](https://ffoodd.github.io/a11y.css) is an interesting end user solution especially for authoring content
* gettext, po, mo are old school and there are new frameworks. there are new options
  * can these techniques apply to text simplification, [accessible numbers](https://accessiblenumbers.com/), maybe even braille?
  * we'll need to understand new syntaxes for translation
* a11y documentation is an exhausting hunting and gathering simulation. my fingers are legs cramped from gathering a11y resources strewn across the vast wasteland of post modernities recklessness. 
did i just create more waste with this document?

## Links

overviews
: [Lost in Translation: Tips for Multilingual Web Accessibility](https://benmyers.dev/blog/multilingual-web-accessibility/) by ben meyers
: [ What they don’t tell you when you translate your app ](https://ericwbailey.website/published/what-they-dont-tell-you-when-you-translate-your-app/) by eric bailey
: [On Language Learning for Screen Reader Users](https://florianbeijers.xyz/on-language-learning-with-a-screenreader) by florian biejers
: [aria label does not translate](https://adrianroselli.com/2019/11/aria-label-does-not-translate.html) by adrian roselli
   
projects
: [project fluent](https://projectfluent.org/)
    : [project fluent js](https://github.com/projectfluent/fluent.js/)
    : [discourse](https://discourse.mozilla.org/c/fluent/262)
: [i18next](https://github.com/i18next)
    : &nbsp;

w3c
: [Choosing a Language Tag](https://www.w3.org/WAI/standards-guidelines/wcag/translations/)
: [Text size in translation](https://www.w3.org/International/articles/article-text-size)
: [articles and tutorials](https://www.w3.org/International/articlelist)

testing
: [testing localization/internationalization](https://www.levelaccess.com/blog/accessibility-considerations-localization/)
: [ Make Sure Every User-Facing String Gets Translated ](https://benmyers.dev/blog/multilingual-web-accessibility/#make-sure-every-user-facing-string-gets-translated)
: [css testing with <ruby><code>a11y.css</code><rt>alix</rt></ruby>](https://ffoodd.github.io/a11y.css)
