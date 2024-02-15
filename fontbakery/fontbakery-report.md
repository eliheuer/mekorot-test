## FontBakery report

fontbakery version: 0.11.1

<h2>Check results</h2><details><summary><b>[14] Mekorot-ExtraBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with ImportError: cannot import name 'unicodes_per_glyphset' from 'glyphsets.definitions' (/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/glyphsets/definitions/__init__.py)
```
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/checkrunner.py", line 170, in _exec_check
    results.extend(list(result))
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts.py", line 1076, in com_google_fonts_check_glyph_coverage
    glyphsets_fulfilled = get_glyphsets_fulfilled(ttFont)
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts_conditions.py", line 748, in get_glyphsets_fulfilled
    from glyphsets.definitions import unicodes_per_glyphset, glyphset_definitions

``` [code: failed-check]
</div></details><details><summary>💔 <b>ERROR:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 💔 **ERROR** Failed with ImportError: cannot import name 'unicodes_per_glyphset' from 'glyphsets.definitions' (/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/glyphsets/definitions/__init__.py)
```
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/checkrunner.py", line 170, in _exec_check
    results.extend(list(result))
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts.py", line 3543, in com_google_fonts_check_glyphsets_shape_languages
    glyphsets_fulfilled = get_glyphsets_fulfilled(ttFont)
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts_conditions.py", line 748, in get_glyphsets_fulfilled
    from glyphsets.definitions import unicodes_per_glyphset, glyphset_definitions

``` [code: failed-check]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, canadian-aboriginal, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, math, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, syriac, malayalam, tai-le, canadian-aboriginal, old-permic, coptic, math
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition
 * U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition
 * U+FB04 LATIN SMALL LIGATURE FFL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `greek-ext`, `hebrew`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- one.lf

	- zero.lf
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<263.0,685.0>--<252.0,562.0>> -> L<<252.0,562.0>--<252.0,424.0>>

	* d (U+0064): L<<584.0,685.0>--<573.0,562.0>> -> L<<573.0,562.0>--<573.0,133.0>>

	* dcaron (U+010F): L<<584.0,685.0>--<573.0,562.0>> -> L<<573.0,562.0>--<573.0,133.0>>

	* dotlessi (U+0131): L<<290.0,489.0>--<280.0,342.0>> -> L<<280.0,342.0>--<280.0,67.0>>

	* f_f_i (U+FB03): L<<1004.0,480.0>--<994.0,342.0>> -> L<<994.0,342.0>--<994.0,67.0>>

	* f_f_i (U+FB03): L<<643.0,476.0>--<838.0,476.0>> -> L<<838.0,476.0>--<953.0,480.0>>

	* f_f_i (U+FB03): L<<838.0,476.0>--<953.0,480.0>> -> L<<953.0,480.0>--<1004.0,480.0>>

	* f_f_l (U+FB04): L<<1005.0,685.0>--<994.0,562.0>> -> L<<994.0,562.0>--<994.0,67.0>>

	* fi (U+FB01): L<<291.0,476.0>--<487.0,476.0>> -> L<<487.0,476.0>--<601.0,480.0>>

	* fi (U+FB01): L<<487.0,476.0>--<601.0,480.0>> -> L<<601.0,480.0>--<653.0,480.0>>

	* fi (U+FB01): L<<653.0,480.0>--<643.0,342.0>> -> L<<643.0,342.0>--<643.0,67.0>>

	* fl (U+FB02): L<<654.0,685.0>--<643.0,562.0>> -> L<<643.0,562.0>--<643.0,67.0>>

	* h (U+0068): L<<276.0,685.0>--<265.0,562.0>> -> L<<265.0,562.0>--<265.0,398.0>>

	* i (U+0069): L<<290.0,489.0>--<280.0,342.0>> -> L<<280.0,342.0>--<280.0,67.0>>

	* iacute (U+00ED): L<<290.0,489.0>--<280.0,342.0>> -> L<<280.0,342.0>--<280.0,67.0>>

	* icircumflex (U+00EE): L<<290.0,489.0>--<280.0,342.0>> -> L<<280.0,342.0>--<280.0,67.0>>

	* idieresis (U+00EF): L<<290.0,489.0>--<280.0,342.0>> -> L<<280.0,342.0>--<280.0,67.0>>

	* igrave (U+00EC): L<<290.0,489.0>--<280.0,342.0>> -> L<<280.0,342.0>--<280.0,67.0>>

	* ij (U+0133): L<<290.0,489.0>--<280.0,342.0>> -> L<<280.0,342.0>--<280.0,67.0>>

	* ij (U+0133): L<<652.0,489.0>--<642.0,342.0>> -> L<<642.0,342.0>--<642.0,39.0>>

	* imacron (U+012B): L<<290.0,489.0>--<280.0,342.0>> -> L<<280.0,342.0>--<280.0,67.0>>

	* iogonek (U+012F): L<<290.0,489.0>--<280.0,342.0>> -> L<<280.0,342.0>--<280.0,67.0>>

	* j (U+006A): L<<281.0,489.0>--<271.0,342.0>> -> L<<271.0,342.0>--<271.0,39.0>>

	* k (U+006B): L<<276.0,685.0>--<265.0,562.0>> -> L<<265.0,562.0>--<265.0,308.0>>

	* l (U+006C): L<<276.0,685.0>--<265.0,562.0>> -> L<<265.0,562.0>--<265.0,67.0>>

	* lacute (U+013A): L<<276.0,685.0>--<265.0,562.0>> -> L<<265.0,562.0>--<265.0,67.0>>

	* lcaron (U+013E): L<<276.0,685.0>--<265.0,562.0>> -> L<<265.0,562.0>--<265.0,67.0>>

	* ldot (U+0140): L<<276.0,685.0>--<265.0,562.0>> -> L<<265.0,562.0>--<265.0,67.0>>

	* lslash (U+0142): L<<295.0,685.0>--<284.0,562.0>> -> L<<284.0,562.0>--<284.0,398.0>>

	* thorn (U+00FE): L<<258.0,685.0>--<247.0,562.0>> -> L<<247.0,562.0>--<247.0,424.0>>

	* u (U+0075): L<<583.0,478.0>--<579.0,402.0>> -> L<<579.0,402.0>--<579.0,133.0>>

	* uacute (U+00FA): L<<583.0,478.0>--<579.0,402.0>> -> L<<579.0,402.0>--<579.0,133.0>>

	* ubreve (U+016D): L<<583.0,478.0>--<579.0,402.0>> -> L<<579.0,402.0>--<579.0,133.0>>

	* ucircumflex (U+00FB): L<<583.0,478.0>--<579.0,402.0>> -> L<<579.0,402.0>--<579.0,133.0>>

	* udieresis (U+00FC): L<<583.0,478.0>--<579.0,402.0>> -> L<<579.0,402.0>--<579.0,133.0>>

	* ugrave (U+00F9): L<<583.0,478.0>--<579.0,402.0>> -> L<<579.0,402.0>--<579.0,133.0>>

	* uhungarumlaut (U+0171): L<<583.0,478.0>--<579.0,402.0>> -> L<<579.0,402.0>--<579.0,133.0>>

	* umacron (U+016B): L<<583.0,478.0>--<579.0,402.0>> -> L<<579.0,402.0>--<579.0,133.0>>

	* uni0137 (U+0137): L<<276.0,685.0>--<265.0,562.0>> -> L<<265.0,562.0>--<265.0,308.0>>

	* uni013C (U+013C): L<<276.0,685.0>--<265.0,562.0>> -> L<<265.0,562.0>--<265.0,67.0>>

	* uni0237 (U+0237): L<<281.0,489.0>--<271.0,342.0>> -> L<<271.0,342.0>--<271.0,39.0>>

	* uogonek (U+0173): L<<583.0,478.0>--<579.0,402.0>> -> L<<579.0,402.0>--<579.0,133.0>>

	* uring (U+016F): L<<583.0,478.0>--<579.0,402.0>> -> L<<579.0,402.0>--<579.0,133.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* R (U+0052): B<<680.0,373.0>-<635.0,327.0>-<539.0,316.0>>/B<<539.0,316.0>-<598.0,312.0>-<629.0,298.5>> = 10.415158151644732

	* Racute (U+0154): B<<680.0,373.0>-<635.0,327.0>-<539.0,316.0>>/B<<539.0,316.0>-<598.0,312.0>-<629.0,298.5>> = 10.415158151644732

	* Rcaron (U+0158): B<<680.0,373.0>-<635.0,327.0>-<539.0,316.0>>/B<<539.0,316.0>-<598.0,312.0>-<629.0,298.5>> = 10.415158151644732

	* eth (U+00F0): B<<358.0,426.0>-<394.0,399.0>-<408.0,356.0>>/B<<408.0,356.0>-<402.0,417.0>-<375.5,459.0>> = 12.416704977003022

	* fi (U+FB01): L<<469.0,67.0>--<469.0,394.0>>/L<<469.0,394.0>--<466.0,376.0>> = 9.462322208025613

	* g (U+0067): B<<53.5,-62.5>-<84.0,-41.0>-<160.0,-35.0>>/B<<160.0,-35.0>-<96.0,-24.0>-<72.5,2.5>> = 14.26641339965503

	* gbreve (U+011F): B<<53.5,-62.5>-<84.0,-41.0>-<160.0,-35.0>>/B<<160.0,-35.0>-<96.0,-24.0>-<72.5,2.5>> = 14.26641339965503

	* gdotaccent (U+0121): B<<53.5,-62.5>-<84.0,-41.0>-<160.0,-35.0>>/B<<160.0,-35.0>-<96.0,-24.0>-<72.5,2.5>> = 14.26641339965503

	* registered (U+00AE): B<<402.0,504.0>-<402.0,453.0>-<343.0,450.0>>/L<<343.0,450.0>--<344.0,450.0>> = 2.910837826167747

	* threequarters (U+00BE): B<<312.5,536.0>-<293.0,516.0>-<248.0,507.0>>/B<<248.0,507.0>-<297.0,505.0>-<325.5,483.5>> = 13.647238333144026

	* uni00B3 (U+00B3): B<<302.5,536.0>-<283.0,516.0>-<238.0,507.0>>/B<<238.0,507.0>-<287.0,505.0>-<315.5,483.5>> = 13.647238333144026

	* uni0123 (U+0123): B<<53.5,-62.5>-<84.0,-41.0>-<160.0,-35.0>>/B<<160.0,-35.0>-<96.0,-24.0>-<72.5,2.5>> = 14.26641339965503

	* uni0156 (U+0156): B<<680.0,373.0>-<635.0,327.0>-<539.0,316.0>>/B<<539.0,316.0>-<598.0,312.0>-<629.0,298.5>> = 10.415158151644732 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* four (U+0034): L<<28.0,183.0>--<27.0,306.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters _should_ disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ ǰ̦ j̦̒ į̦̀

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Avokaya (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Cicipu (Latn, 44,000 speakers), Yala (Latn, 200,000 speakers), Lugbara (Latn, 2,200,000 speakers), Basaa (Latn, 332,940 speakers), Nateni (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Nzakara (Latn, 50,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Mundani (Latn, 34,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Koonzime (Latn, 40,000 speakers), Zapotec (Latn, 490,000 speakers), Ebira (Latn, 2,200,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Ma’di (Latn, 584,000 speakers), Igbo (Latn, 27,823,640 speakers), Ekpeye (Latn, 226,000 speakers), Dan (Latn, 1,099,244 speakers), Aghem (Latn, 38,843 speakers), Gulay (Latn, 250,478 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ejagham (Latn, 120,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Mango (Latn, 77,000 speakers), Mfumte (Latn, 79,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Sar (Latn, 500,000 speakers), Navajo (Latn, 166,319 speakers), Makaa (Latn, 221,000 speakers), Dii (Latn, 71,000 speakers), Southern Kisi (Latn, 360,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] Mekorot-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with ImportError: cannot import name 'unicodes_per_glyphset' from 'glyphsets.definitions' (/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/glyphsets/definitions/__init__.py)
```
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/checkrunner.py", line 170, in _exec_check
    results.extend(list(result))
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts.py", line 1076, in com_google_fonts_check_glyph_coverage
    glyphsets_fulfilled = get_glyphsets_fulfilled(ttFont)
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts_conditions.py", line 748, in get_glyphsets_fulfilled
    from glyphsets.definitions import unicodes_per_glyphset, glyphset_definitions

``` [code: failed-check]
</div></details><details><summary>💔 <b>ERROR:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 💔 **ERROR** Failed with ImportError: cannot import name 'unicodes_per_glyphset' from 'glyphsets.definitions' (/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/glyphsets/definitions/__init__.py)
```
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/checkrunner.py", line 170, in _exec_check
    results.extend(list(result))
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts.py", line 3543, in com_google_fonts_check_glyphsets_shape_languages
    glyphsets_fulfilled = get_glyphsets_fulfilled(ttFont)
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts_conditions.py", line 748, in get_glyphsets_fulfilled
    from glyphsets.definitions import unicodes_per_glyphset, glyphset_definitions

``` [code: failed-check]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, canadian-aboriginal, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, math, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, syriac, malayalam, tai-le, canadian-aboriginal, old-permic, coptic, math
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition
 * U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition
 * U+FB04 LATIN SMALL LIGATURE FFL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `greek-ext`, `hebrew`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- one.lf

	- zero.lf
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<212.0,683.0>--<202.0,580.0>> -> L<<202.0,580.0>--<202.0,426.0>>

	* d (U+0064): L<<545.0,683.0>--<536.0,580.0>> -> L<<536.0,580.0>--<536.0,117.0>>

	* dcaron (U+010F): L<<545.0,683.0>--<536.0,580.0>> -> L<<536.0,580.0>--<536.0,117.0>>

	* dcroat (U+0111): L<<545.0,683.0>--<536.0,580.0>> -> L<<536.0,580.0>--<536.0,569.0>>

	* dotlessi (U+0131): L<<241.0,482.0>--<233.0,366.0>> -> L<<233.0,366.0>--<233.0,64.0>>

	* f_f_i (U+FB03): L<<553.0,472.0>--<755.0,472.0>> -> L<<755.0,472.0>--<841.0,480.0>>

	* f_f_i (U+FB03): L<<755.0,472.0>--<841.0,480.0>> -> L<<841.0,480.0>--<876.0,480.0>>

	* f_f_i (U+FB03): L<<876.0,480.0>--<868.0,366.0>> -> L<<868.0,366.0>--<868.0,64.0>>

	* f_f_l (U+FB04): L<<878.0,683.0>--<868.0,580.0>> -> L<<868.0,580.0>--<868.0,64.0>>

	* fi (U+FB01): L<<237.0,472.0>--<440.0,472.0>> -> L<<440.0,472.0>--<526.0,480.0>>

	* fi (U+FB01): L<<440.0,472.0>--<526.0,480.0>> -> L<<526.0,480.0>--<560.0,480.0>>

	* fi (U+FB01): L<<560.0,480.0>--<553.0,366.0>> -> L<<553.0,366.0>--<553.0,64.0>>

	* fl (U+FB02): L<<562.0,683.0>--<553.0,580.0>> -> L<<553.0,580.0>--<553.0,64.0>>

	* h (U+0068): L<<228.0,683.0>--<218.0,580.0>> -> L<<218.0,580.0>--<218.0,395.0>>

	* hbar (U+0127): L<<228.0,683.0>--<218.0,580.0>> -> L<<218.0,580.0>--<218.0,569.0>>

	* i (U+0069): L<<241.0,482.0>--<233.0,366.0>> -> L<<233.0,366.0>--<233.0,64.0>>

	* iacute (U+00ED): L<<241.0,482.0>--<233.0,366.0>> -> L<<233.0,366.0>--<233.0,64.0>>

	* icircumflex (U+00EE): L<<241.0,482.0>--<233.0,366.0>> -> L<<233.0,366.0>--<233.0,64.0>>

	* idieresis (U+00EF): L<<241.0,482.0>--<233.0,366.0>> -> L<<233.0,366.0>--<233.0,64.0>>

	* igrave (U+00EC): L<<241.0,482.0>--<233.0,366.0>> -> L<<233.0,366.0>--<233.0,64.0>>

	* ij (U+0133): L<<241.0,482.0>--<233.0,366.0>> -> L<<233.0,366.0>--<233.0,64.0>>

	* ij (U+0133): L<<563.0,482.0>--<556.0,366.0>> -> L<<556.0,366.0>--<556.0,23.0>>

	* imacron (U+012B): L<<241.0,482.0>--<233.0,366.0>> -> L<<233.0,366.0>--<233.0,64.0>>

	* iogonek (U+012F): L<<241.0,482.0>--<233.0,366.0>> -> L<<233.0,366.0>--<233.0,64.0>>

	* j (U+006A): L<<229.0,482.0>--<222.0,366.0>> -> L<<222.0,366.0>--<222.0,23.0>>

	* k (U+006B): L<<228.0,683.0>--<218.0,580.0>> -> L<<218.0,580.0>--<218.0,302.0>>

	* k (U+006B): L<<434.0,0.0>--<434.0,45.0>> -> L<<434.0,45.0>--<433.0,56.0>>

	* l (U+006C): L<<229.0,683.0>--<219.0,580.0>> -> L<<219.0,580.0>--<219.0,64.0>>

	* lacute (U+013A): L<<229.0,683.0>--<219.0,580.0>> -> L<<219.0,580.0>--<219.0,64.0>>

	* lcaron (U+013E): L<<229.0,683.0>--<219.0,580.0>> -> L<<219.0,580.0>--<219.0,64.0>>

	* ldot (U+0140): L<<229.0,683.0>--<219.0,580.0>> -> L<<219.0,580.0>--<219.0,64.0>>

	* lslash (U+0142): L<<254.0,683.0>--<244.0,580.0>> -> L<<244.0,580.0>--<244.0,393.0>>

	* quotedbl (U+0022): L<<175.0,650.0>--<175.0,628.0>> -> L<<175.0,628.0>--<155.0,403.0>>

	* quotedbl (U+0022): L<<253.0,403.0>--<233.0,628.0>> -> L<<233.0,628.0>--<233.0,650.0>>

	* quotedbl (U+0022): L<<351.0,650.0>--<351.0,628.0>> -> L<<351.0,628.0>--<331.0,403.0>>

	* quotedbl (U+0022): L<<77.0,403.0>--<57.0,628.0>> -> L<<57.0,628.0>--<57.0,650.0>>

	* quotesingle (U+0027): L<<175.0,650.0>--<175.0,628.0>> -> L<<175.0,628.0>--<155.0,403.0>>

	* quotesingle (U+0027): L<<77.0,403.0>--<57.0,628.0>> -> L<<57.0,628.0>--<57.0,650.0>>

	* thorn (U+00FE): L<<206.0,683.0>--<196.0,580.0>> -> L<<196.0,580.0>--<196.0,426.0>>

	* u (U+0075): L<<533.0,476.0>--<526.0,403.0>> -> L<<526.0,403.0>--<526.0,117.0>>

	* uacute (U+00FA): L<<533.0,476.0>--<526.0,403.0>> -> L<<526.0,403.0>--<526.0,117.0>>

	* ubreve (U+016D): L<<533.0,476.0>--<526.0,403.0>> -> L<<526.0,403.0>--<526.0,117.0>>

	* ucircumflex (U+00FB): L<<533.0,476.0>--<526.0,403.0>> -> L<<526.0,403.0>--<526.0,117.0>>

	* udieresis (U+00FC): L<<533.0,476.0>--<526.0,403.0>> -> L<<526.0,403.0>--<526.0,117.0>>

	* ugrave (U+00F9): L<<533.0,476.0>--<526.0,403.0>> -> L<<526.0,403.0>--<526.0,117.0>>

	* uhungarumlaut (U+0171): L<<533.0,476.0>--<526.0,403.0>> -> L<<526.0,403.0>--<526.0,117.0>>

	* umacron (U+016B): L<<533.0,476.0>--<526.0,403.0>> -> L<<526.0,403.0>--<526.0,117.0>>

	* uni0137 (U+0137): L<<228.0,683.0>--<218.0,580.0>> -> L<<218.0,580.0>--<218.0,302.0>>

	* uni0137 (U+0137): L<<434.0,0.0>--<434.0,45.0>> -> L<<434.0,45.0>--<433.0,56.0>>

	* uni013C (U+013C): L<<229.0,683.0>--<219.0,580.0>> -> L<<219.0,580.0>--<219.0,64.0>>

	* uni0237 (U+0237): L<<229.0,482.0>--<222.0,366.0>> -> L<<222.0,366.0>--<222.0,23.0>>

	* uogonek (U+0173): L<<533.0,476.0>--<526.0,403.0>> -> L<<526.0,403.0>--<526.0,117.0>>

	* uring (U+016F): L<<533.0,476.0>--<526.0,403.0>> -> L<<526.0,403.0>--<526.0,117.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<373.0,431.0>-<413.0,401.0>-<430.0,350.0>>/B<<430.0,350.0>-<418.0,472.0>-<303.0,544.0>> = 12.817368232795141

	* registered (U+00AE): B<<376.0,512.0>-<376.0,465.0>-<328.0,462.0>>/B<<328.0,462.0>-<347.0,460.0>-<355.5,452.0>> = 9.585340332491795

	* threequarters (U+00BE): B<<289.0,533.5>-<270.0,513.0>-<230.0,505.0>>/B<<230.0,505.0>-<278.0,503.0>-<304.5,481.5>> = 13.695876504408998

	* uni00B3 (U+00B3): B<<282.0,533.5>-<263.0,513.0>-<223.0,505.0>>/B<<223.0,505.0>-<271.0,503.0>-<297.5,481.5>> = 13.695876504408998 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters _should_ disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ ǰ̦ j̦̒ į̦̀

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Avokaya (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Cicipu (Latn, 44,000 speakers), Yala (Latn, 200,000 speakers), Lugbara (Latn, 2,200,000 speakers), Basaa (Latn, 332,940 speakers), Nateni (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Nzakara (Latn, 50,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Mundani (Latn, 34,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Koonzime (Latn, 40,000 speakers), Zapotec (Latn, 490,000 speakers), Ebira (Latn, 2,200,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Ma’di (Latn, 584,000 speakers), Igbo (Latn, 27,823,640 speakers), Ekpeye (Latn, 226,000 speakers), Dan (Latn, 1,099,244 speakers), Aghem (Latn, 38,843 speakers), Gulay (Latn, 250,478 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ejagham (Latn, 120,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Mango (Latn, 77,000 speakers), Mfumte (Latn, 79,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Sar (Latn, 500,000 speakers), Navajo (Latn, 166,319 speakers), Makaa (Latn, 221,000 speakers), Dii (Latn, 71,000 speakers), Southern Kisi (Latn, 360,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[14] Mekorot-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with ImportError: cannot import name 'unicodes_per_glyphset' from 'glyphsets.definitions' (/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/glyphsets/definitions/__init__.py)
```
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/checkrunner.py", line 170, in _exec_check
    results.extend(list(result))
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts.py", line 1076, in com_google_fonts_check_glyph_coverage
    glyphsets_fulfilled = get_glyphsets_fulfilled(ttFont)
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts_conditions.py", line 748, in get_glyphsets_fulfilled
    from glyphsets.definitions import unicodes_per_glyphset, glyphset_definitions

``` [code: failed-check]
</div></details><details><summary>💔 <b>ERROR:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 💔 **ERROR** Failed with ImportError: cannot import name 'unicodes_per_glyphset' from 'glyphsets.definitions' (/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/glyphsets/definitions/__init__.py)
```
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/checkrunner.py", line 170, in _exec_check
    results.extend(list(result))
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts.py", line 3543, in com_google_fonts_check_glyphsets_shape_languages
    glyphsets_fulfilled = get_glyphsets_fulfilled(ttFont)
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts_conditions.py", line 748, in get_glyphsets_fulfilled
    from glyphsets.definitions import unicodes_per_glyphset, glyphset_definitions

``` [code: failed-check]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, canadian-aboriginal, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, math, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, syriac, malayalam, tai-le, canadian-aboriginal, old-permic, coptic, math
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition
 * U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition
 * U+FB04 LATIN SMALL LIGATURE FFL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `greek-ext`, `hebrew`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- one.lf

	- zero.lf
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment B<<132.0,144.0>-<138.0,144.0>-<151.5,132.0>>

	* dollar (U+0024) contains a short segment B<<492.0,506.0>-<485.0,506.0>-<472.0,518.0>>

	* seven (U+0037) contains a short segment L<<570.0,650.0>--<570.0,637.0>>

	* at (U+0040) contains a short segment L<<524.0,249.0>--<515.0,249.0>>

	* at (U+0040) contains a short segment B<<615.0,236.0>-<610.0,220.0>-<608.0,207.5>>

	* at (U+0040) contains a short segment B<<608.0,207.5>-<606.0,195.0>-<606.0,185.0>>

	* at (U+0040) contains a short segment B<<606.0,185.0>-<607.0,162.0>-<619.0,152.0>>

	* f (U+0066) contains a short segment L<<119.0,483.0>--<119.0,486.0>>

	* g (U+0067) contains a short segment B<<540.0,480.0>-<551.0,480.0>-<554.0,473.0>>

	* g (U+0067) contains a short segment B<<553.5,407.0>-<550.0,395.0>-<544.0,395.0>>

	* k (U+006B) contains a short segment L<<441.0,45.0>--<440.0,54.0>>

	* m (U+006D) contains a short segment L<<185.0,486.0>--<211.0,486.0>>

	* m (U+006D) contains a short segment B<<561.0,358.0>-<561.0,354.0>-<561.0,348.0>>

	* cent (U+00A2) contains a short segment B<<375.0,572.0>-<379.0,572.0>-<382.0,572.0>>

	* sterling (U+00A3) contains a short segment B<<299.0,295.0>-<301.0,284.0>-<301.0,273.0>>

	* section (U+00A7) contains a short segment B<<153.0,29.0>-<157.0,29.0>-<168.0,19.0>>

	* section (U+00A7) contains a short segment B<<482.0,519.0>-<477.0,519.0>-<466.0,529.5>>

	* germandbls (U+00DF) contains a short segment L<<119.0,483.0>--<119.0,486.0>>

	* dcroat (U+0111) contains a short segment L<<548.0,574.0>--<548.0,572.0>>

	* gbreve (U+011F) contains a short segment B<<540.0,480.0>-<551.0,480.0>-<554.0,473.0>>

	* gbreve (U+011F) contains a short segment B<<553.5,407.0>-<550.0,395.0>-<544.0,395.0>>

	* gdotaccent (U+0121) contains a short segment B<<540.0,480.0>-<551.0,480.0>-<554.0,473.0>>

	* gdotaccent (U+0121) contains a short segment B<<553.5,407.0>-<550.0,395.0>-<544.0,395.0>>

	* uni0123 (U+0123) contains a short segment B<<540.0,480.0>-<551.0,480.0>-<554.0,473.0>>

	* uni0123 (U+0123) contains a short segment B<<553.5,407.0>-<550.0,395.0>-<544.0,395.0>>

	* hbar (U+0127) contains a short segment L<<234.0,574.0>--<234.0,572.0>>

	* uni0137 (U+0137) contains a short segment L<<441.0,45.0>--<440.0,54.0>>

	* Eng (U+014A) contains a short segment B<<430.0,-77.0>-<438.0,-77.0>-<453.0,-88.0>>

	* scedilla (U+015F) contains a short segment B<<152.5,-151.5>-<161.0,-144.0>-<169.0,-144.0>>

	* scedilla (U+015F) contains a short segment B<<169.0,-144.0>-<174.0,-144.0>-<184.0,-151.0>>

	* scedilla (U+015F) contains a short segment B<<277.0,-143.0>-<277.0,-133.0>-<270.0,-126.0>>

	* scedilla (U+015F) contains a short segment L<<238.0,-10.0>--<233.0,-10.0>>

	* uni05D0 (U+05D0) contains a short segment B<<109.5,422.0>-<118.0,431.0>-<118.0,439.0>>

	* uni05D0 (U+05D0) contains a short segment B<<118.0,439.0>-<118.0,445.0>-<113.5,449.5>>

	* uni05D0 (U+05D0) contains a short segment B<<113.5,449.5>-<109.0,454.0>-<95.0,455.0>>

	* uni05D0 (U+05D0) contains a short segment B<<63.0,634.0>-<71.0,634.0>-<77.5,633.0>>

	* uni05D0 (U+05D0) contains a short segment B<<77.5,633.0>-<84.0,632.0>-<92.0,632.0>>

	* uni05D0 (U+05D0) contains a short segment B<<181.0,647.0>-<181.0,641.0>-<184.0,637.5>>

	* uni05D0 (U+05D0) contains a short segment B<<184.0,637.5>-<187.0,634.0>-<198.0,634.0>>

	* uni05D2 (U+05D2) contains a short segment B<<300.0,165.0>-<307.0,165.0>-<310.5,168.0>>

	* uni05D2 (U+05D2) contains a short segment B<<310.5,168.0>-<314.0,171.0>-<314.0,181.0>>

	* uni05D7 (U+05D7) contains a short segment B<<76.0,681.0>-<80.0,688.0>-<90.0,693.0>>

	* uni05D8 (U+05D8) contains a short segment B<<254.5,180.5>-<256.0,173.0>-<258.0,170.0>>

	* uni05D8 (U+05D8) contains a short segment B<<229.0,-8.0>-<223.0,-8.0>-<218.0,-22.5>>

	* uni05DB (U+05DB) contains a short segment B<<83.0,708.0>-<89.0,708.0>-<94.5,703.5>>

	* uni05DD (U+05DD) contains a short segment B<<117.0,702.0>-<122.0,702.0>-<127.5,698.0>>

	* uni05E1 (U+05E1) contains a short segment B<<125.0,702.0>-<132.0,702.0>-<135.5,693.5>>

	* uni05E1 (U+05E1) contains a short segment B<<138.0,75.5>-<132.0,84.0>-<128.0,84.0>>

	* uni05E1 (U+05E1) contains a short segment B<<128.0,84.0>-<123.0,84.0>-<121.0,79.0>>

	* uni05E1 (U+05E1) contains a short segment B<<121.0,79.0>-<119.0,74.0>-<119.0,68.0>>

	* uni05E4 (U+05E4) contains a short segment B<<126.0,444.0>-<126.0,453.0>-<117.0,459.0>>

	* uni05E9 (U+05E9) contains a short segment B<<192.5,463.5>-<183.0,460.0>-<183.0,448.0>>

	* uni05EA (U+05EA) contains a short segment B<<133.0,459.0>-<133.0,464.0>-<124.5,469.5>>

	* Euro (U+20AC) contains a short segment B<<553.0,131.5>-<564.0,143.0>-<571.0,143.0>>

	* Euro (U+20AC) contains a short segment B<<570.0,507.0>-<563.0,507.0>-<552.5,518.5>>

	* f_f (U+FB00) contains a short segment B<<798.0,536.0>-<791.0,536.0>-<782.0,547.0>>

	* fi (U+FB01) contains a short segment L<<119.0,483.0>--<119.0,486.0>>

	* fi (U+FB01) contains a short segment B<<483.0,534.0>-<475.0,534.0>-<465.0,545.0>>

	* fl (U+FB02) contains a short segment L<<119.0,483.0>--<119.0,486.0>>

	* f_f_i (U+FB03) contains a short segment L<<25.0,412.0>--<25.0,446.0>>

	* f_f_i (U+FB03) contains a short segment B<<810.0,534.0>-<803.0,534.0>-<793.0,545.0>>

	* f_f_l (U+FB04) contains a short segment L<<25.0,412.0>--<25.0,446.0>>

	* f_f_l (U+FB04) contains a short segment L<<888.0,684.0>--<920.0,684.0>>

	* uniFB2A (U+FB2A) contains a short segment B<<192.5,463.5>-<183.0,460.0>-<183.0,448.0>>

	* uniFB2B (U+FB2B) contains a short segment B<<192.5,463.5>-<183.0,460.0>-<183.0,448.0>>

	* uniFB2C (U+FB2C) contains a short segment B<<192.5,463.5>-<183.0,460.0>-<183.0,448.0>>

	* uniFB2D (U+FB2D) contains a short segment B<<192.5,463.5>-<183.0,460.0>-<183.0,448.0>>

	* uniFB2E (U+FB2E) contains a short segment B<<109.5,422.0>-<118.0,431.0>-<118.0,439.0>>

	* uniFB2E (U+FB2E) contains a short segment B<<118.0,439.0>-<118.0,445.0>-<113.5,449.5>>

	* uniFB2E (U+FB2E) contains a short segment B<<113.5,449.5>-<109.0,454.0>-<95.0,455.0>>

	* uniFB2E (U+FB2E) contains a short segment B<<63.0,634.0>-<71.0,634.0>-<77.5,633.0>>

	* uniFB2E (U+FB2E) contains a short segment B<<77.5,633.0>-<84.0,632.0>-<92.0,632.0>>

	* uniFB2E (U+FB2E) contains a short segment B<<181.0,647.0>-<181.0,641.0>-<184.0,637.5>>

	* uniFB2E (U+FB2E) contains a short segment B<<184.0,637.5>-<187.0,634.0>-<198.0,634.0>>

	* uniFB2F (U+FB2F) contains a short segment B<<109.5,422.0>-<118.0,431.0>-<118.0,439.0>>

	* uniFB2F (U+FB2F) contains a short segment B<<118.0,439.0>-<118.0,445.0>-<113.5,449.5>>

	* uniFB2F (U+FB2F) contains a short segment B<<113.5,449.5>-<109.0,454.0>-<95.0,455.0>>

	* uniFB2F (U+FB2F) contains a short segment B<<63.0,634.0>-<71.0,634.0>-<77.5,633.0>>

	* uniFB2F (U+FB2F) contains a short segment B<<77.5,633.0>-<84.0,632.0>-<92.0,632.0>>

	* uniFB2F (U+FB2F) contains a short segment B<<181.0,647.0>-<181.0,641.0>-<184.0,637.5>>

	* uniFB2F (U+FB2F) contains a short segment B<<184.0,637.5>-<187.0,634.0>-<198.0,634.0>>

	* uniFB30 (U+FB30) contains a short segment B<<109.5,422.0>-<118.0,431.0>-<118.0,439.0>>

	* uniFB30 (U+FB30) contains a short segment B<<118.0,439.0>-<118.0,445.0>-<113.5,449.5>>

	* uniFB30 (U+FB30) contains a short segment B<<113.5,449.5>-<109.0,454.0>-<95.0,455.0>>

	* uniFB30 (U+FB30) contains a short segment B<<63.0,634.0>-<71.0,634.0>-<77.5,633.0>>

	* uniFB30 (U+FB30) contains a short segment B<<77.5,633.0>-<84.0,632.0>-<92.0,632.0>>

	* uniFB30 (U+FB30) contains a short segment B<<181.0,647.0>-<181.0,641.0>-<184.0,637.5>>

	* uniFB30 (U+FB30) contains a short segment B<<184.0,637.5>-<187.0,634.0>-<198.0,634.0>>

	* uniFB32 (U+FB32) contains a short segment B<<300.0,165.0>-<307.0,165.0>-<310.5,168.0>>

	* uniFB32 (U+FB32) contains a short segment B<<310.5,168.0>-<314.0,171.0>-<314.0,181.0>>

	* uniFB38 (U+FB38) contains a short segment B<<254.5,180.5>-<256.0,173.0>-<258.0,170.0>>

	* uniFB38 (U+FB38) contains a short segment B<<229.0,-8.0>-<223.0,-8.0>-<218.0,-22.5>>

	* uniFB3B (U+FB3B) contains a short segment B<<83.0,708.0>-<89.0,708.0>-<94.5,703.5>>

	* uniFB41 (U+FB41) contains a short segment B<<125.0,702.0>-<132.0,702.0>-<135.5,693.5>>

	* uniFB41 (U+FB41) contains a short segment B<<138.0,75.5>-<132.0,84.0>-<128.0,84.0>>

	* uniFB41 (U+FB41) contains a short segment B<<128.0,84.0>-<123.0,84.0>-<121.0,79.0>>

	* uniFB41 (U+FB41) contains a short segment B<<121.0,79.0>-<119.0,74.0>-<119.0,68.0>>

	* uniFB44 (U+FB44) contains a short segment B<<126.0,444.0>-<126.0,453.0>-<117.0,459.0>>

	* uniFB49 (U+FB49) contains a short segment B<<192.5,463.5>-<183.0,460.0>-<183.0,448.0>>

	* uniFB4A (U+FB4A) contains a short segment B<<133.0,459.0>-<133.0,464.0>-<124.5,469.5>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<229.0,684.0>--<219.0,574.0>> -> L<<219.0,574.0>--<219.0,425.0>>

	* d (U+0064): L<<558.0,684.0>--<548.0,574.0>> -> L<<548.0,574.0>--<548.0,122.0>>

	* dcaron (U+010F): L<<558.0,684.0>--<548.0,574.0>> -> L<<548.0,574.0>--<548.0,122.0>>

	* dcroat (U+0111): L<<558.0,684.0>--<548.0,574.0>> -> L<<548.0,574.0>--<548.0,572.0>>

	* dotlessi (U+0131): L<<257.0,484.0>--<249.0,358.0>> -> L<<249.0,358.0>--<249.0,65.0>>

	* f_f_i (U+FB03): L<<583.0,473.0>--<783.0,473.0>> -> L<<783.0,473.0>--<878.0,480.0>>

	* f_f_i (U+FB03): L<<783.0,473.0>--<878.0,480.0>> -> L<<878.0,480.0>--<919.0,480.0>>

	* f_f_i (U+FB03): L<<919.0,480.0>--<910.0,358.0>> -> L<<910.0,358.0>--<910.0,65.0>>

	* f_f_l (U+FB04): L<<920.0,684.0>--<910.0,574.0>> -> L<<910.0,574.0>--<910.0,65.0>>

	* fi (U+FB01): L<<255.0,473.0>--<456.0,473.0>> -> L<<456.0,473.0>--<551.0,480.0>>

	* fi (U+FB01): L<<456.0,473.0>--<551.0,480.0>> -> L<<551.0,480.0>--<591.0,480.0>>

	* fi (U+FB01): L<<591.0,480.0>--<583.0,358.0>> -> L<<583.0,358.0>--<583.0,65.0>>

	* fl (U+FB02): L<<593.0,684.0>--<583.0,574.0>> -> L<<583.0,574.0>--<583.0,65.0>>

	* h (U+0068): L<<244.0,684.0>--<234.0,574.0>> -> L<<234.0,574.0>--<234.0,396.0>>

	* hbar (U+0127): L<<244.0,684.0>--<234.0,574.0>> -> L<<234.0,574.0>--<234.0,572.0>>

	* i (U+0069): L<<257.0,484.0>--<249.0,358.0>> -> L<<249.0,358.0>--<249.0,65.0>>

	* iacute (U+00ED): L<<257.0,484.0>--<249.0,358.0>> -> L<<249.0,358.0>--<249.0,65.0>>

	* icircumflex (U+00EE): L<<257.0,484.0>--<249.0,358.0>> -> L<<249.0,358.0>--<249.0,65.0>>

	* idieresis (U+00EF): L<<257.0,484.0>--<249.0,358.0>> -> L<<249.0,358.0>--<249.0,65.0>>

	* igrave (U+00EC): L<<257.0,484.0>--<249.0,358.0>> -> L<<249.0,358.0>--<249.0,65.0>>

	* ij (U+0133): L<<257.0,484.0>--<249.0,358.0>> -> L<<249.0,358.0>--<249.0,65.0>>

	* ij (U+0133): L<<592.0,484.0>--<584.0,358.0>> -> L<<584.0,358.0>--<584.0,28.0>>

	* imacron (U+012B): L<<257.0,484.0>--<249.0,358.0>> -> L<<249.0,358.0>--<249.0,65.0>>

	* iogonek (U+012F): L<<257.0,484.0>--<249.0,358.0>> -> L<<249.0,358.0>--<249.0,65.0>>

	* j (U+006A): L<<246.0,484.0>--<238.0,358.0>> -> L<<238.0,358.0>--<238.0,28.0>>

	* k (U+006B): L<<244.0,684.0>--<234.0,574.0>> -> L<<234.0,574.0>--<234.0,304.0>>

	* l (U+006C): L<<245.0,684.0>--<234.0,574.0>> -> L<<234.0,574.0>--<234.0,65.0>>

	* lacute (U+013A): L<<245.0,684.0>--<234.0,574.0>> -> L<<234.0,574.0>--<234.0,65.0>>

	* lcaron (U+013E): L<<245.0,684.0>--<234.0,574.0>> -> L<<234.0,574.0>--<234.0,65.0>>

	* ldot (U+0140): L<<245.0,684.0>--<234.0,574.0>> -> L<<234.0,574.0>--<234.0,65.0>>

	* lslash (U+0142): L<<268.0,684.0>--<257.0,574.0>> -> L<<257.0,574.0>--<257.0,394.0>>

	* quotedbl (U+0022): L<<184.0,650.0>--<184.0,625.0>> -> L<<184.0,625.0>--<163.0,396.0>>

	* quotedbl (U+0022): L<<265.0,396.0>--<243.0,625.0>> -> L<<243.0,625.0>--<243.0,650.0>>

	* quotedbl (U+0022): L<<372.0,650.0>--<372.0,625.0>> -> L<<372.0,625.0>--<351.0,396.0>>

	* quotedbl (U+0022): L<<77.0,396.0>--<55.0,625.0>> -> L<<55.0,625.0>--<55.0,650.0>>

	* quotesingle (U+0027): L<<184.0,650.0>--<184.0,625.0>> -> L<<184.0,625.0>--<163.0,396.0>>

	* quotesingle (U+0027): L<<77.0,396.0>--<55.0,625.0>> -> L<<55.0,625.0>--<55.0,650.0>>

	* thorn (U+00FE): L<<223.0,684.0>--<213.0,574.0>> -> L<<213.0,574.0>--<213.0,425.0>>

	* u (U+0075): L<<550.0,477.0>--<544.0,403.0>> -> L<<544.0,403.0>--<544.0,122.0>>

	* uacute (U+00FA): L<<550.0,477.0>--<544.0,403.0>> -> L<<544.0,403.0>--<544.0,122.0>>

	* ubreve (U+016D): L<<550.0,477.0>--<544.0,403.0>> -> L<<544.0,403.0>--<544.0,122.0>>

	* ucircumflex (U+00FB): L<<550.0,477.0>--<544.0,403.0>> -> L<<544.0,403.0>--<544.0,122.0>>

	* udieresis (U+00FC): L<<550.0,477.0>--<544.0,403.0>> -> L<<544.0,403.0>--<544.0,122.0>>

	* ugrave (U+00F9): L<<550.0,477.0>--<544.0,403.0>> -> L<<544.0,403.0>--<544.0,122.0>>

	* uhungarumlaut (U+0171): L<<550.0,477.0>--<544.0,403.0>> -> L<<544.0,403.0>--<544.0,122.0>>

	* umacron (U+016B): L<<550.0,477.0>--<544.0,403.0>> -> L<<544.0,403.0>--<544.0,122.0>>

	* uni0137 (U+0137): L<<244.0,684.0>--<234.0,574.0>> -> L<<234.0,574.0>--<234.0,304.0>>

	* uni013C (U+013C): L<<245.0,684.0>--<234.0,574.0>> -> L<<234.0,574.0>--<234.0,65.0>>

	* uni0237 (U+0237): L<<246.0,484.0>--<238.0,358.0>> -> L<<238.0,358.0>--<238.0,28.0>>

	* uogonek (U+0173): L<<550.0,477.0>--<544.0,403.0>> -> L<<544.0,403.0>--<544.0,122.0>>

	* uring (U+016F): L<<550.0,477.0>--<544.0,403.0>> -> L<<544.0,403.0>--<544.0,122.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<368.0,429.0>-<406.0,400.0>-<423.0,352.0>>/B<<423.0,352.0>-<417.0,414.0>-<387.0,459.5>> = 13.97490835500601

	* registered (U+00AE): B<<385.0,509.0>-<385.0,461.0>-<333.0,458.0>>/B<<333.0,458.0>-<355.0,456.0>-<363.5,448.0>> = 8.496294582169769

	* threequarters (U+00BE): B<<297.0,534.5>-<278.0,514.0>-<236.0,505.0>>/B<<236.0,505.0>-<284.0,504.0>-<311.5,482.5>> = 13.2882465009941

	* uni00B3 (U+00B3): B<<289.0,534.5>-<270.0,514.0>-<228.0,505.0>>/B<<228.0,505.0>-<276.0,504.0>-<303.5,482.5>> = 13.2882465009941 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters _should_ disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ ǰ̦ j̦̒ į̦̀

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Avokaya (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Cicipu (Latn, 44,000 speakers), Yala (Latn, 200,000 speakers), Lugbara (Latn, 2,200,000 speakers), Basaa (Latn, 332,940 speakers), Nateni (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Nzakara (Latn, 50,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Mundani (Latn, 34,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Koonzime (Latn, 40,000 speakers), Zapotec (Latn, 490,000 speakers), Ebira (Latn, 2,200,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Ma’di (Latn, 584,000 speakers), Igbo (Latn, 27,823,640 speakers), Ekpeye (Latn, 226,000 speakers), Dan (Latn, 1,099,244 speakers), Aghem (Latn, 38,843 speakers), Gulay (Latn, 250,478 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ejagham (Latn, 120,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Mango (Latn, 77,000 speakers), Mfumte (Latn, 79,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Sar (Latn, 500,000 speakers), Navajo (Latn, 166,319 speakers), Makaa (Latn, 221,000 speakers), Dii (Latn, 71,000 speakers), Southern Kisi (Latn, 360,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[14] Mekorot-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with ImportError: cannot import name 'unicodes_per_glyphset' from 'glyphsets.definitions' (/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/glyphsets/definitions/__init__.py)
```
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/checkrunner.py", line 170, in _exec_check
    results.extend(list(result))
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts.py", line 1076, in com_google_fonts_check_glyph_coverage
    glyphsets_fulfilled = get_glyphsets_fulfilled(ttFont)
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts_conditions.py", line 748, in get_glyphsets_fulfilled
    from glyphsets.definitions import unicodes_per_glyphset, glyphset_definitions

``` [code: failed-check]
</div></details><details><summary>💔 <b>ERROR:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 💔 **ERROR** Failed with ImportError: cannot import name 'unicodes_per_glyphset' from 'glyphsets.definitions' (/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/glyphsets/definitions/__init__.py)
```
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/checkrunner.py", line 170, in _exec_check
    results.extend(list(result))
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts.py", line 3543, in com_google_fonts_check_glyphsets_shape_languages
    glyphsets_fulfilled = get_glyphsets_fulfilled(ttFont)
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts_conditions.py", line 748, in get_glyphsets_fulfilled
    from glyphsets.definitions import unicodes_per_glyphset, glyphset_definitions

``` [code: failed-check]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, canadian-aboriginal, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, math, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, syriac, malayalam, tai-le, canadian-aboriginal, old-permic, coptic, math
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition
 * U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition
 * U+FB04 LATIN SMALL LIGATURE FFL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `greek-ext`, `hebrew`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- one.lf

	- zero.lf
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<255.0,685.0>--<244.0,565.0>> -> L<<244.0,565.0>--<244.0,424.0>>

	* d (U+0064): L<<578.0,685.0>--<567.0,565.0>> -> L<<567.0,565.0>--<567.0,130.0>>

	* dcaron (U+010F): L<<578.0,685.0>--<567.0,565.0>> -> L<<567.0,565.0>--<567.0,130.0>>

	* dotlessi (U+0131): L<<282.0,488.0>--<272.0,346.0>> -> L<<272.0,346.0>--<272.0,67.0>>

	* f_f_i (U+FB03): L<<628.0,475.0>--<824.0,475.0>> -> L<<824.0,475.0>--<934.0,480.0>>

	* f_f_i (U+FB03): L<<824.0,475.0>--<934.0,480.0>> -> L<<934.0,480.0>--<983.0,480.0>>

	* f_f_i (U+FB03): L<<983.0,480.0>--<973.0,346.0>> -> L<<973.0,346.0>--<973.0,67.0>>

	* f_f_l (U+FB04): L<<984.0,685.0>--<973.0,565.0>> -> L<<973.0,565.0>--<973.0,67.0>>

	* fi (U+FB01): L<<282.0,475.0>--<479.0,475.0>> -> L<<479.0,475.0>--<589.0,480.0>>

	* fi (U+FB01): L<<479.0,475.0>--<589.0,480.0>> -> L<<589.0,480.0>--<638.0,480.0>>

	* fi (U+FB01): L<<638.0,480.0>--<628.0,346.0>> -> L<<628.0,346.0>--<628.0,67.0>>

	* fl (U+FB02): L<<639.0,685.0>--<628.0,565.0>> -> L<<628.0,565.0>--<628.0,67.0>>

	* h (U+0068): L<<268.0,685.0>--<257.0,565.0>> -> L<<257.0,565.0>--<257.0,397.0>>

	* i (U+0069): L<<282.0,488.0>--<272.0,346.0>> -> L<<272.0,346.0>--<272.0,67.0>>

	* iacute (U+00ED): L<<282.0,488.0>--<272.0,346.0>> -> L<<272.0,346.0>--<272.0,67.0>>

	* icircumflex (U+00EE): L<<282.0,488.0>--<272.0,346.0>> -> L<<272.0,346.0>--<272.0,67.0>>

	* idieresis (U+00EF): L<<282.0,488.0>--<272.0,346.0>> -> L<<272.0,346.0>--<272.0,67.0>>

	* igrave (U+00EC): L<<282.0,488.0>--<272.0,346.0>> -> L<<272.0,346.0>--<272.0,67.0>>

	* ij (U+0133): L<<282.0,488.0>--<272.0,346.0>> -> L<<272.0,346.0>--<272.0,67.0>>

	* ij (U+0133): L<<637.0,488.0>--<628.0,346.0>> -> L<<628.0,346.0>--<628.0,36.0>>

	* imacron (U+012B): L<<282.0,488.0>--<272.0,346.0>> -> L<<272.0,346.0>--<272.0,67.0>>

	* iogonek (U+012F): L<<282.0,488.0>--<272.0,346.0>> -> L<<272.0,346.0>--<272.0,67.0>>

	* j (U+006A): L<<272.0,488.0>--<263.0,346.0>> -> L<<263.0,346.0>--<263.0,36.0>>

	* k (U+006B): L<<268.0,685.0>--<257.0,565.0>> -> L<<257.0,565.0>--<257.0,307.0>>

	* k (U+006B): L<<451.0,0.0>--<451.0,46.0>> -> L<<451.0,46.0>--<451.0,52.0>>

	* l (U+006C): L<<268.0,685.0>--<257.0,565.0>> -> L<<257.0,565.0>--<257.0,67.0>>

	* lacute (U+013A): L<<268.0,685.0>--<257.0,565.0>> -> L<<257.0,565.0>--<257.0,67.0>>

	* lcaron (U+013E): L<<268.0,685.0>--<257.0,565.0>> -> L<<257.0,565.0>--<257.0,67.0>>

	* ldot (U+0140): L<<268.0,685.0>--<257.0,565.0>> -> L<<257.0,565.0>--<257.0,67.0>>

	* lslash (U+0142): L<<288.0,685.0>--<277.0,565.0>> -> L<<277.0,565.0>--<277.0,397.0>>

	* thorn (U+00FE): L<<249.0,685.0>--<239.0,565.0>> -> L<<239.0,565.0>--<239.0,424.0>>

	* u (U+0075): L<<575.0,478.0>--<570.0,402.0>> -> L<<570.0,402.0>--<570.0,130.0>>

	* uacute (U+00FA): L<<575.0,478.0>--<570.0,402.0>> -> L<<570.0,402.0>--<570.0,130.0>>

	* ubreve (U+016D): L<<575.0,478.0>--<570.0,402.0>> -> L<<570.0,402.0>--<570.0,130.0>>

	* ucircumflex (U+00FB): L<<575.0,478.0>--<570.0,402.0>> -> L<<570.0,402.0>--<570.0,130.0>>

	* udieresis (U+00FC): L<<575.0,478.0>--<570.0,402.0>> -> L<<570.0,402.0>--<570.0,130.0>>

	* ugrave (U+00F9): L<<575.0,478.0>--<570.0,402.0>> -> L<<570.0,402.0>--<570.0,130.0>>

	* uhungarumlaut (U+0171): L<<575.0,478.0>--<570.0,402.0>> -> L<<570.0,402.0>--<570.0,130.0>>

	* umacron (U+016B): L<<575.0,478.0>--<570.0,402.0>> -> L<<570.0,402.0>--<570.0,130.0>>

	* uni0137 (U+0137): L<<268.0,685.0>--<257.0,565.0>> -> L<<257.0,565.0>--<257.0,307.0>>

	* uni0137 (U+0137): L<<451.0,0.0>--<451.0,46.0>> -> L<<451.0,46.0>--<451.0,52.0>>

	* uni013C (U+013C): L<<268.0,685.0>--<257.0,565.0>> -> L<<257.0,565.0>--<257.0,67.0>>

	* uni0237 (U+0237): L<<272.0,488.0>--<263.0,346.0>> -> L<<263.0,346.0>--<263.0,36.0>>

	* uogonek (U+0173): L<<575.0,478.0>--<570.0,402.0>> -> L<<570.0,402.0>--<570.0,130.0>>

	* uring (U+016F): L<<575.0,478.0>--<570.0,402.0>> -> L<<570.0,402.0>--<570.0,130.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* R (U+0052): B<<668.5,374.5>-<625.0,329.0>-<533.0,317.0>>/B<<533.0,317.0>-<588.0,313.0>-<617.5,299.5>> = 11.591050264885148

	* Racute (U+0154): B<<668.5,374.5>-<625.0,329.0>-<533.0,317.0>>/B<<533.0,317.0>-<588.0,313.0>-<617.5,299.5>> = 11.591050264885148

	* Rcaron (U+0158): B<<668.5,374.5>-<625.0,329.0>-<533.0,317.0>>/B<<533.0,317.0>-<588.0,313.0>-<617.5,299.5>> = 11.591050264885148

	* eth (U+00F0): B<<360.5,426.5>-<397.0,399.0>-<412.0,355.0>>/B<<412.0,355.0>-<406.0,416.0>-<378.5,459.0>> = 13.207129428113227

	* registered (U+00AE): B<<398.0,505.0>-<398.0,455.0>-<341.0,452.0>>/B<<341.0,452.0>-<365.0,451.0>-<375.0,443.0>> = 5.398731534572079

	* threequarters (U+00BE): B<<309.5,536.0>-<290.0,516.0>-<245.0,506.0>>/B<<245.0,506.0>-<294.0,505.0>-<322.5,483.5>> = 13.69794703705892

	* uni00B3 (U+00B3): B<<299.5,536.0>-<280.0,516.0>-<235.0,506.0>>/B<<235.0,506.0>-<284.0,505.0>-<312.5,483.5>> = 13.69794703705892

	* uni0156 (U+0156): B<<668.5,374.5>-<625.0,329.0>-<533.0,317.0>>/B<<533.0,317.0>-<588.0,313.0>-<617.5,299.5>> = 11.591050264885148 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* four (U+0034): L<<28.0,185.0>--<27.0,303.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters _should_ disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ ǰ̦ j̦̒ į̦̀

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Avokaya (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Cicipu (Latn, 44,000 speakers), Yala (Latn, 200,000 speakers), Lugbara (Latn, 2,200,000 speakers), Basaa (Latn, 332,940 speakers), Nateni (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Nzakara (Latn, 50,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Mundani (Latn, 34,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Koonzime (Latn, 40,000 speakers), Zapotec (Latn, 490,000 speakers), Ebira (Latn, 2,200,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Ma’di (Latn, 584,000 speakers), Igbo (Latn, 27,823,640 speakers), Ekpeye (Latn, 226,000 speakers), Dan (Latn, 1,099,244 speakers), Aghem (Latn, 38,843 speakers), Gulay (Latn, 250,478 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ejagham (Latn, 120,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Mango (Latn, 77,000 speakers), Mfumte (Latn, 79,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Sar (Latn, 500,000 speakers), Navajo (Latn, 166,319 speakers), Makaa (Latn, 221,000 speakers), Dii (Latn, 71,000 speakers), Southern Kisi (Latn, 360,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] Mekorot-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with ImportError: cannot import name 'unicodes_per_glyphset' from 'glyphsets.definitions' (/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/glyphsets/definitions/__init__.py)
```
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/checkrunner.py", line 170, in _exec_check
    results.extend(list(result))
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts.py", line 1076, in com_google_fonts_check_glyph_coverage
    glyphsets_fulfilled = get_glyphsets_fulfilled(ttFont)
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts_conditions.py", line 748, in get_glyphsets_fulfilled
    from glyphsets.definitions import unicodes_per_glyphset, glyphset_definitions

``` [code: failed-check]
</div></details><details><summary>💔 <b>ERROR:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 💔 **ERROR** Failed with ImportError: cannot import name 'unicodes_per_glyphset' from 'glyphsets.definitions' (/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/glyphsets/definitions/__init__.py)
```
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/checkrunner.py", line 170, in _exec_check
    results.extend(list(result))
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts.py", line 3543, in com_google_fonts_check_glyphsets_shape_languages
    glyphsets_fulfilled = get_glyphsets_fulfilled(ttFont)
  File "/home/runner/work/mekorot-test/mekorot-test/venv-test/lib/python3.10/site-packages/fontbakery/profiles/googlefonts_conditions.py", line 748, in get_glyphsets_fulfilled
    from glyphsets.definitions import unicodes_per_glyphset, glyphset_definitions

``` [code: failed-check]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, canadian-aboriginal, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, math, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, syriac, malayalam, tai-le, canadian-aboriginal, old-permic, coptic, math
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition
 * U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition
 * U+FB04 LATIN SMALL LIGATURE FFL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `greek-ext`, `hebrew`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- one.lf

	- zero.lf
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* b (U+0062): L<<246.0,684.0>--<235.0,568.0>> -> L<<235.0,568.0>--<235.0,424.0>>

	* d (U+0064): L<<571.0,684.0>--<561.0,568.0>> -> L<<561.0,568.0>--<561.0,128.0>>

	* dcaron (U+010F): L<<571.0,684.0>--<561.0,568.0>> -> L<<561.0,568.0>--<561.0,128.0>>

	* dotlessi (U+0131): L<<274.0,487.0>--<264.0,350.0>> -> L<<264.0,350.0>--<264.0,66.0>>

	* f_f_i (U+FB03): L<<613.0,475.0>--<810.0,475.0>> -> L<<810.0,475.0>--<916.0,480.0>>

	* f_f_i (U+FB03): L<<810.0,475.0>--<916.0,480.0>> -> L<<916.0,480.0>--<961.0,480.0>>

	* f_f_i (U+FB03): L<<961.0,480.0>--<952.0,350.0>> -> L<<952.0,350.0>--<952.0,66.0>>

	* f_f_l (U+FB04): L<<963.0,684.0>--<952.0,568.0>> -> L<<952.0,568.0>--<952.0,66.0>>

	* fi (U+FB01): L<<273.0,475.0>--<471.0,475.0>> -> L<<471.0,475.0>--<576.0,480.0>>

	* fi (U+FB01): L<<471.0,475.0>--<576.0,480.0>> -> L<<576.0,480.0>--<622.0,480.0>>

	* fi (U+FB01): L<<622.0,480.0>--<613.0,350.0>> -> L<<613.0,350.0>--<613.0,66.0>>

	* fl (U+FB02): L<<623.0,684.0>--<613.0,568.0>> -> L<<613.0,568.0>--<613.0,66.0>>

	* h (U+0068): L<<260.0,684.0>--<249.0,568.0>> -> L<<249.0,568.0>--<249.0,397.0>>

	* i (U+0069): L<<274.0,487.0>--<264.0,350.0>> -> L<<264.0,350.0>--<264.0,66.0>>

	* iacute (U+00ED): L<<274.0,487.0>--<264.0,350.0>> -> L<<264.0,350.0>--<264.0,66.0>>

	* icircumflex (U+00EE): L<<274.0,487.0>--<264.0,350.0>> -> L<<264.0,350.0>--<264.0,66.0>>

	* idieresis (U+00EF): L<<274.0,487.0>--<264.0,350.0>> -> L<<264.0,350.0>--<264.0,66.0>>

	* igrave (U+00EC): L<<274.0,487.0>--<264.0,350.0>> -> L<<264.0,350.0>--<264.0,66.0>>

	* ij (U+0133): L<<274.0,487.0>--<264.0,350.0>> -> L<<264.0,350.0>--<264.0,66.0>>

	* ij (U+0133): L<<623.0,487.0>--<614.0,350.0>> -> L<<614.0,350.0>--<614.0,34.0>>

	* imacron (U+012B): L<<274.0,487.0>--<264.0,350.0>> -> L<<264.0,350.0>--<264.0,66.0>>

	* iogonek (U+012F): L<<274.0,487.0>--<264.0,350.0>> -> L<<264.0,350.0>--<264.0,66.0>>

	* j (U+006A): L<<264.0,487.0>--<255.0,350.0>> -> L<<255.0,350.0>--<255.0,34.0>>

	* k (U+006B): L<<260.0,684.0>--<249.0,568.0>> -> L<<249.0,568.0>--<249.0,306.0>>

	* k (U+006B): L<<447.0,0.0>--<447.0,46.0>> -> L<<447.0,46.0>--<447.0,53.0>>

	* l (U+006C): L<<260.0,684.0>--<250.0,568.0>> -> L<<250.0,568.0>--<250.0,66.0>>

	* lacute (U+013A): L<<260.0,684.0>--<250.0,568.0>> -> L<<250.0,568.0>--<250.0,66.0>>

	* lcaron (U+013E): L<<260.0,684.0>--<250.0,568.0>> -> L<<250.0,568.0>--<250.0,66.0>>

	* ldot (U+0140): L<<260.0,684.0>--<250.0,568.0>> -> L<<250.0,568.0>--<250.0,66.0>>

	* lslash (U+0142): L<<281.0,684.0>--<271.0,568.0>> -> L<<271.0,568.0>--<271.0,396.0>>

	* m (U+006D): L<<579.0,353.0>--<579.0,349.0>> -> L<<579.0,349.0>--<579.0,63.0>>

	* thorn (U+00FE): L<<241.0,684.0>--<230.0,568.0>> -> L<<230.0,568.0>--<230.0,425.0>>

	* u (U+0075): L<<566.0,477.0>--<561.0,402.0>> -> L<<561.0,402.0>--<561.0,128.0>>

	* uacute (U+00FA): L<<566.0,477.0>--<561.0,402.0>> -> L<<561.0,402.0>--<561.0,128.0>>

	* ubreve (U+016D): L<<566.0,477.0>--<561.0,402.0>> -> L<<561.0,402.0>--<561.0,128.0>>

	* ucircumflex (U+00FB): L<<566.0,477.0>--<561.0,402.0>> -> L<<561.0,402.0>--<561.0,128.0>>

	* udieresis (U+00FC): L<<566.0,477.0>--<561.0,402.0>> -> L<<561.0,402.0>--<561.0,128.0>>

	* ugrave (U+00F9): L<<566.0,477.0>--<561.0,402.0>> -> L<<561.0,402.0>--<561.0,128.0>>

	* uhungarumlaut (U+0171): L<<566.0,477.0>--<561.0,402.0>> -> L<<561.0,402.0>--<561.0,128.0>>

	* umacron (U+016B): L<<566.0,477.0>--<561.0,402.0>> -> L<<561.0,402.0>--<561.0,128.0>>

	* uni0137 (U+0137): L<<260.0,684.0>--<249.0,568.0>> -> L<<249.0,568.0>--<249.0,306.0>>

	* uni0137 (U+0137): L<<447.0,0.0>--<447.0,46.0>> -> L<<447.0,46.0>--<447.0,53.0>>

	* uni013C (U+013C): L<<260.0,684.0>--<250.0,568.0>> -> L<<250.0,568.0>--<250.0,66.0>>

	* uni0237 (U+0237): L<<264.0,487.0>--<255.0,350.0>> -> L<<255.0,350.0>--<255.0,34.0>>

	* uogonek (U+0173): L<<566.0,477.0>--<561.0,402.0>> -> L<<561.0,402.0>--<561.0,128.0>>

	* uring (U+016F): L<<566.0,477.0>--<561.0,402.0>> -> L<<561.0,402.0>--<561.0,128.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Outline Correctness Checks.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* R (U+0052): B<<656.5,375.5>-<615.0,331.0>-<527.0,319.0>>/B<<527.0,319.0>-<578.0,314.0>-<606.0,301.0>> = 13.364505354945878

	* Racute (U+0154): B<<656.5,375.5>-<615.0,331.0>-<527.0,319.0>>/B<<527.0,319.0>-<578.0,314.0>-<606.0,301.0>> = 13.364505354945878

	* Rcaron (U+0158): B<<656.5,375.5>-<615.0,331.0>-<527.0,319.0>>/B<<527.0,319.0>-<578.0,314.0>-<606.0,301.0>> = 13.364505354945878

	* eth (U+00F0): B<<363.0,427.5>-<400.0,399.0>-<415.0,354.0>>/B<<415.0,354.0>-<409.0,415.0>-<381.0,459.0>> = 12.817368232795141

	* registered (U+00AE): B<<393.0,507.0>-<393.0,457.0>-<339.0,454.0>>/B<<339.0,454.0>-<362.0,453.0>-<371.5,445.0>> = 5.669383041863348

	* threequarters (U+00BE): B<<305.0,535.5>-<286.0,515.0>-<242.0,506.0>>/B<<242.0,506.0>-<290.0,504.0>-<318.0,482.5>> = 13.946074824606567

	* uni00B3 (U+00B3): B<<296.0,535.5>-<277.0,515.0>-<233.0,506.0>>/B<<233.0,506.0>-<281.0,504.0>-<309.0,482.5>> = 13.946074824606567

	* uni0156 (U+0156): B<<656.5,375.5>-<615.0,331.0>-<527.0,319.0>>/B<<527.0,319.0>-<578.0,314.0>-<606.0,301.0>> = 13.364505354945878 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters _should_ disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ ǰ̦ j̦̒ į̦̀

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Avokaya (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Cicipu (Latn, 44,000 speakers), Yala (Latn, 200,000 speakers), Lugbara (Latn, 2,200,000 speakers), Basaa (Latn, 332,940 speakers), Nateni (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Nzakara (Latn, 50,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Mundani (Latn, 34,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Koonzime (Latn, 40,000 speakers), Zapotec (Latn, 490,000 speakers), Ebira (Latn, 2,200,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Ma’di (Latn, 584,000 speakers), Igbo (Latn, 27,823,640 speakers), Ekpeye (Latn, 226,000 speakers), Dan (Latn, 1,099,244 speakers), Aghem (Latn, 38,843 speakers), Gulay (Latn, 250,478 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ejagham (Latn, 120,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Mango (Latn, 77,000 speakers), Mfumte (Latn, 79,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Sar (Latn, 500,000 speakers), Navajo (Latn, 166,319 speakers), Makaa (Latn, 221,000 speakers), Dii (Latn, 71,000 speakers), Southern Kisi (Latn, 360,000 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | ☠ FATAL | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| 10 | 0 | 0 | 58 | 612 | 31 | 513 | 0 |
| 1% | 0% | 0% | 5% | 50% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
