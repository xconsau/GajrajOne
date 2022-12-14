## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[7] GajrajOne-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


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

	- And 35 more.

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

	* Ba.dv (U+092C): L<<307.0,331.0>--<310.0,237.0>> -> L<<310.0,237.0>--<310.0,132.0>>

	* Ba.dv (U+092C): L<<310.0,428.0>--<384.0,298.0>> -> L<<384.0,298.0>--<418.0,230.0>>

	* Ba.dv (U+092C): L<<420.0,134.0>--<342.0,271.0>> -> L<<342.0,271.0>--<312.0,331.0>>

	* Ba.dv (U+092C): L<<423.0,230.0>--<420.0,324.0>> -> L<<420.0,324.0>--<420.0,579.0>>

	* Delta (U+0394): L<<430.0,573.0>--<417.0,500.0>> -> L<<417.0,500.0>--<309.0,68.0>>

	* Delta (U+0394): L<<562.0,68.0>--<455.0,500.0>> -> L<<455.0,500.0>--<442.0,573.0>>

	* Gcommaaccent (U+0122): L<<300.0,-278.0>--<310.0,-83.0>> -> L<<310.0,-83.0>--<310.0,-60.0>>

	* Kcommaaccent (U+0136): L<<300.0,-278.0>--<310.0,-83.0>> -> L<<310.0,-83.0>--<310.0,-60.0>>

	* Lcommaaccent (U+013B): L<<223.0,-278.0>--<233.0,-83.0>> -> L<<233.0,-83.0>--<233.0,-60.0>>

	* Ncommaaccent (U+0145): L<<307.0,-278.0>--<317.0,-83.0>> -> L<<317.0,-83.0>--<317.0,-60.0>> 

	* And 79 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Om.dv (U+0950): L<<640.0,68.0>--<905.0,67.0>>

	* U (U+0055): L<<741.0,558.0>--<740.0,344.0>>

	* Uacute (U+00DA): L<<741.0,558.0>--<740.0,344.0>>

	* Ubreve (U+016C): L<<741.0,558.0>--<740.0,344.0>>

	* Ucircumflex (U+00DB): L<<741.0,558.0>--<740.0,344.0>>

	* Udieresis (U+00DC): L<<741.0,558.0>--<740.0,344.0>>

	* Ugrave (U+00D9): L<<741.0,558.0>--<740.0,344.0>>

	* Uhungarumlaut (U+0170): L<<741.0,558.0>--<740.0,344.0>>

	* Umacron (U+016A): L<<741.0,558.0>--<740.0,344.0>>

	* Uogonek (U+0172): L<<741.0,558.0>--<740.0,344.0>> 

	* And 16 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 0 | 7 | 113 | 8 | 99 | 0 |
| 0% | 0% | 3% | 50% | 4% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
