## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[10] GajrajOne-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.695x (1695) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: X	Contours detected: 3	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: g	Contours detected: 1	Expected: 2 or 3

	- Glyph name: x	Contours detected: 3	Expected: 1

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: gcircumflex	Contours detected: 2	Expected: 3 or 4

	- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

	- Glyph name: gdotaccent	Contours detected: 2	Expected: 3 or 4 

	- And 66 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 acute (U+00B4), breve (U+02D8), caron (U+02C7), cedilla (U+00B8), circumflex (U+02C6), commaaccentcomb (U+0326), dieresis (U+00A8), dotaccent (U+02D9), grave (U+0060), hungarumlaut (U+02DD) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 Nukta.dv (U+093C), acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 9 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0060, U+00A8, U+00AF, U+00B4, U+00B8, U+02C6, U+02C7, U+02D8, U+02D9, U+02DA and 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Cha.dv (U+091B): L<<597.0,500.0>--<641.0,500.0>> -> L<<641.0,500.0>--<707.0,500.0>>

	* Cha.dv (U+091B): L<<653.0,438.0>--<641.0,438.0>> -> L<<641.0,438.0>--<630.0,438.0>>

	* Chandrabindu.dv (U+0901): L<<-170.0,815.0>--<-170.0,894.0>> -> L<<-170.0,894.0>--<-170.0,900.0>>

	* Chandrabindu.dv (U+0901): L<<-50.0,913.0>--<-50.0,834.0>> -> L<<-50.0,834.0>--<-50.0,828.0>>

	* D (U+0044): L<<30.0,665.0>--<320.0,665.0>> -> L<<320.0,665.0>--<526.0,665.0>>

	* D (U+0044): L<<526.0,0.0>--<320.0,0.0>> -> L<<320.0,0.0>--<30.0,0.0>>

	* Dcaron (U+010E): L<<30.0,665.0>--<320.0,665.0>> -> L<<320.0,665.0>--<526.0,665.0>>

	* Dcaron (U+010E): L<<526.0,0.0>--<320.0,0.0>> -> L<<320.0,0.0>--<30.0,0.0>>

	* Dcroat (U+0110): L<<50.0,665.0>--<340.0,665.0>> -> L<<340.0,665.0>--<546.0,665.0>>

	* Dcroat (U+0110): L<<546.0,0.0>--<340.0,0.0>> -> L<<340.0,0.0>--<50.0,0.0>> 

	* And 64 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<379.5,327.5>-<398.0,321.0>-<399.0,310.0>>/L<<399.0,310.0>--<399.0,432.0>> = 5.1944289077348

	* aacute (U+00E1): B<<379.5,327.5>-<398.0,321.0>-<399.0,310.0>>/L<<399.0,310.0>--<399.0,432.0>> = 5.1944289077348

	* abreve (U+0103): B<<379.5,327.5>-<398.0,321.0>-<399.0,310.0>>/L<<399.0,310.0>--<399.0,432.0>> = 5.1944289077348

	* acaron (U+01CE): B<<379.5,327.5>-<398.0,321.0>-<399.0,310.0>>/L<<399.0,310.0>--<399.0,432.0>> = 5.1944289077348

	* acircumflex (U+00E2): B<<379.5,327.5>-<398.0,321.0>-<399.0,310.0>>/L<<399.0,310.0>--<399.0,432.0>> = 5.1944289077348

	* adieresis (U+00E4): B<<379.5,327.5>-<398.0,321.0>-<399.0,310.0>>/L<<399.0,310.0>--<399.0,432.0>> = 5.1944289077348

	* ae (U+00E6): B<<379.5,327.5>-<398.0,321.0>-<399.0,310.0>>/L<<399.0,310.0>--<399.0,432.0>> = 5.1944289077348

	* agrave (U+00E0): B<<379.5,327.5>-<398.0,321.0>-<399.0,310.0>>/L<<399.0,310.0>--<399.0,432.0>> = 5.1944289077348

	* amacron (U+0101): B<<379.5,327.5>-<398.0,321.0>-<399.0,310.0>>/L<<399.0,310.0>--<399.0,432.0>> = 5.1944289077348

	* aogonek (U+0105): B<<379.5,327.5>-<398.0,321.0>-<399.0,310.0>>/L<<399.0,310.0>--<399.0,432.0>> = 5.1944289077348 

	* And 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Aath.dv (U+096E): L<<132.0,642.0>--<372.0,640.0>>

	* Aath.dv (U+096E): L<<377.0,291.0>--<617.0,289.0>>

	* Cha.dv (U+091B): L<<931.0,302.0>--<930.0,175.0>>

	* Ek.dv (U+0967): L<<344.0,1.0>--<104.0,-1.0>>

	* Om.dv (U+0950): L<<640.0,68.0>--<905.0,67.0>>

	* Om.dv (U+0950): L<<859.0,455.0>--<860.0,310.0>>

	* W (U+0057): L<<811.0,278.0>--<810.0,536.0>>

	* Wacute (U+1E82): L<<811.0,278.0>--<810.0,536.0>>

	* Wcircumflex (U+0174): L<<811.0,278.0>--<810.0,536.0>>

	* Wdieresis (U+1E84): L<<811.0,278.0>--<810.0,536.0>> 

	* And 21 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 0 | 10 | 113 | 8 | 96 | 0 |
| 0% | 0% | 4% | 50% | 4% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
