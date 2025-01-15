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

<dl>
<dt>overviews</dt>
<dd><a href="https://benmyers.dev/blog/multilingual-web-accessibility/">Lost in Translation: Tips for Multilingual Web Accessibility</a> by ben meyers</dd>
<dd><a href="https://ericwbailey.website/published/what-they-dont-tell-you-when-you-translate-your-app/"> What they don’t tell you when you translate your app </a> by eric bailey</dd>
<dd><a href="https://florianbeijers.xyz/on-language-learning-with-a-screenreader">On Language Learning for Screen Reader Users</a> by florian biejers</dd>
<dd><a href="https://adrianroselli.com/2019/11/aria-label-does-not-translate.html">aria label does not translate</a> by adrian roselli</dd>
<dt>projects</dt>
<dd>
<dl>
<dt><a href="https://projectfluent.org/">project fluent</a></dt>
<dd><a href="https://github.com/projectfluent/fluent.js/">project fluent js</a></dd>
<dd><a href="https://discourse.mozilla.org/c/fluent/262">discourse</a></dd>
</dl>
</dd>
<dd>
<dl>
<dt><a href="https://github.com/i18next">i18next</a></dt>
<dd>&nbsp;</dd>
</dl>
</dd>
<dt>w3c</dt>
<dd><a href="https://www.w3.org/WAI/standards-guidelines/wcag/translations/">Choosing a Language Tag</a></dd>
<dd><a href="https://www.w3.org/International/articles/article-text-size">Text size in translation</a></dd>
<dd><a href="https://www.w3.org/International/articlelist">aticles and tutorials</a></dd>
<dt>testing</dt>
<dd><a href="https://www.levelaccess.com/blog/accessibility-considerations-localization/">testing localization/internationalization</a></dd>
<dd><a href="https://benmyers.dev/blog/multilingual-web-accessibility/#make-sure-every-user-facing-string-gets-translated"> Make Sure Every User-Facing String Gets Translated </a></dd>
<dd><a href="https://ffoodd.github.io/a11y.css">css testing with <ruby><code>a11y.css</code><rt>alix</rt></ruby></a></dd>
</dl>
