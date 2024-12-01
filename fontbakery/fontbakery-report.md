## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[19] Menbere-Bold.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>tcaron uses component uni030C.</p>
 [code: wrong-mark]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+0265: LATIN SMALL LETTER TURNED H</td>
<td align="left">U+A78D: LATIN CAPITAL LETTER TURNED H</td>
</tr>
<tr>
<td align="left">U+026F: LATIN SMALL LETTER TURNED M</td>
<td align="left">U+019C: LATIN CAPITAL LETTER TURNED M</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1483, but got 1476 instead</p>
 [code: ascent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Name table records must not have trailing spaces. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name table record with key = (3, 1, 1033, 9) has trailing spaces that must be removed: ' Aleme Tadesse '</p>
 [code: trailing-space]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to J</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ha_Latn (Hausa)</td>
<td align="left">Shaper didn't attach tildecomb to r</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to R</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE4</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yo_Latn (Yoruba)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB9</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bm_Latn (Bambara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dyu_Latn (Dyula)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lg_Latn (Ganda)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set.</p>
 [code: missing]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2024 The Menbere project authors&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni01C2	Contours detected: 3	Expected: 1

- Glyph name: uni01EA	Contours detected: 3	Expected: 2

- Glyph name: uni01EB	Contours detected: 3	Expected: 2

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: uni01C2	Contours detected: 3	Expected: 1

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 660 among a set of 5 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 657:
equal</p>
<p>Width = 659:
logicalnot</p>
<p>Width = 627:
plusminus, approxequal</p>
<p>Width = 504:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Dcroat.001

- overscorecomb
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, coptic, malayalam, duployan, tai-le, syriac, tifinagh, math, old-permic, canadian-aboriginal, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: duployan, cherokee, syriac</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+032F COMBINING INVERTED BREVE BELOW: try adding math</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: math, cherokee, syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: sunuwar, caucasian-albanian, thai, syriac, gothic, tifinagh, cherokee</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EAD LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EC6 LATIN CAPITAL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EC7 LATIN SMALL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ED8 LATIN CAPITAL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ED9 LATIN SMALL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2116 NUMERO SIGN: try adding cyrillic</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols</li>
<li>U+2195 UP DOWN ARROW: try adding one of: math, symbols</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: mahajani, caucasian-albanian, rejang, warang-citi, limbu, masaram-gondi, telugu, canadian-aboriginal, khojki, yi, kannada, malayalam, kharoshthi, tai-le, math, ahom, newa, takri, miao, new-tai-lue, syriac, siddham, duployan, tifinagh, armenian, thai, gujarati, khmer, saurashtra, khudawadi, elbasan, adlam, psalter-pahlavi, gunjala-gondi, meetei-mayek, mende-kikakui, dogra, zanabazar-square, tamil, tai-tham, tirhuta, symbols, hanunoo, batak, lepcha, oriya, bhaiksuki, tagalog, gurmukhi, mongolian, sharada, javanese, wancho, sinhala, hebrew, myanmar, pahawh-hmong, sogdian, devanagari, chakma, syloti-nagri, buhid, nko, bengali, tagbanwa, modi, mandaic, lao, osage, balinese, music, marchen, kaithi, brahmi, kayah-li, buginese, tibetan, soyombo, phags-pa, bassa-vah, coptic, manichaean, thaana, hanifi-rohingya, sundanese, cham, grantha, old-permic, tai-viet</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>ethiopic</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ḭ̀ ḭ́ ḭ̂ ḭ̃ ḭ̄ ḭ̆ ḭ̇ ḭ̈ ḭ̊ ḭ̋ ḭ̌ ḭ̏ ḭ̑ ḭ̒ į̆ į̇ į̈ į̊ į̋ į̏</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Makaa (Latn, 221,000 speakers), Ekpeye (Latn, 226,000 speakers), Cicipu (Latn, 44,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ma’di (Latn, 584,000 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Basaa (Latn, 332,940 speakers), Avokaya (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Fur (Latn, 1,230,163 speakers), Sar (Latn, 500,000 speakers), Dii (Latn, 71,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Nzakara (Latn, 50,000 speakers), Bafut (Latn, 158,146 speakers), Ejagham (Latn, 120,000 speakers), Mfumte (Latn, 79,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Kom (Latn, 360,685 speakers), Koonzime (Latn, 40,000 speakers), South Central Banda (Latn, 244,000 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Vute (Latn, 21,000 speakers), Mango (Latn, 77,000 speakers), Aghem (Latn, 38,843 speakers), Southern Kisi (Latn, 360,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Navajo (Latn, 166,319 speakers), Heiltsuk (Latn, 300 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Han (Latn, 6 speakers), Gulay (Latn, 250,478 speakers), Dutch (Latn, 31,709,104 speakers), Yala (Latn, 200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* W (U+0057): B&lt;&lt;313.5,203.5&gt;-&lt;318.0,175.0&gt;-&lt;318.0,163.0&gt;&gt;/B&lt;&lt;318.0,163.0&gt;-&lt;321.0,221.0&gt;-&lt;333.5,280.5&gt;&gt; = 2.9609361341637563

* W (U+0057): B&lt;&lt;522.0,456.5&gt;-&lt;519.0,442.0&gt;-&lt;520.0,451.0&gt;&gt;/L&lt;&lt;520.0,451.0&gt;--&lt;414.0,0.0&gt;&gt; = 6.886165327021434

* W (U+0057): B&lt;&lt;569.5,581.0&gt;-&lt;562.0,620.0&gt;-&lt;557.0,653.0&gt;&gt;/B&lt;&lt;557.0,653.0&gt;-&lt;557.0,643.0&gt;-&lt;552.5,616.5&gt;&gt; = 8.615648184164108

* W (U+0057): B&lt;&lt;789.5,216.5&gt;-&lt;795.0,184.0&gt;-&lt;798.0,163.0&gt;&gt;/B&lt;&lt;798.0,163.0&gt;-&lt;799.0,180.0&gt;-&lt;804.0,213.0&gt;&gt; = 11.496563017585768

* W (U+0057): L&lt;&lt;175.0,858.0&gt;--&lt;278.0,387.0&gt;&gt;/B&lt;&lt;278.0,387.0&gt;-&lt;277.0,395.0&gt;-&lt;280.5,378.5&gt;&gt; = 5.210443006962688

* Wacute (U+1E82): B&lt;&lt;313.5,203.5&gt;-&lt;318.0,175.0&gt;-&lt;318.0,163.0&gt;&gt;/B&lt;&lt;318.0,163.0&gt;-&lt;321.0,221.0&gt;-&lt;333.5,280.5&gt;&gt; = 2.9609361341637563

* Wacute (U+1E82): B&lt;&lt;522.0,456.5&gt;-&lt;519.0,442.0&gt;-&lt;520.0,451.0&gt;&gt;/L&lt;&lt;520.0,451.0&gt;--&lt;414.0,0.0&gt;&gt; = 6.886165327021434

* Wacute (U+1E82): B&lt;&lt;569.5,581.0&gt;-&lt;562.0,620.0&gt;-&lt;557.0,653.0&gt;&gt;/B&lt;&lt;557.0,653.0&gt;-&lt;557.0,643.0&gt;-&lt;552.5,616.5&gt;&gt; = 8.615648184164108

* Wacute (U+1E82): B&lt;&lt;789.5,216.5&gt;-&lt;795.0,184.0&gt;-&lt;798.0,163.0&gt;&gt;/B&lt;&lt;798.0,163.0&gt;-&lt;799.0,180.0&gt;-&lt;804.0,213.0&gt;&gt; = 11.496563017585768

* Wacute (U+1E82): L&lt;&lt;175.0,858.0&gt;--&lt;278.0,387.0&gt;&gt;/B&lt;&lt;278.0,387.0&gt;-&lt;277.0,395.0&gt;-&lt;280.5,378.5&gt;&gt; = 5.210443006962688

* Wcircumflex (U+0174): B&lt;&lt;313.5,203.5&gt;-&lt;318.0,175.0&gt;-&lt;318.0,163.0&gt;&gt;/B&lt;&lt;318.0,163.0&gt;-&lt;321.0,221.0&gt;-&lt;333.5,280.5&gt;&gt; = 2.9609361341637563

* Wcircumflex (U+0174): B&lt;&lt;522.0,456.5&gt;-&lt;519.0,442.0&gt;-&lt;520.0,451.0&gt;&gt;/L&lt;&lt;520.0,451.0&gt;--&lt;414.0,0.0&gt;&gt; = 6.886165327021434

* Wcircumflex (U+0174): B&lt;&lt;569.5,581.0&gt;-&lt;562.0,620.0&gt;-&lt;557.0,653.0&gt;&gt;/B&lt;&lt;557.0,653.0&gt;-&lt;557.0,643.0&gt;-&lt;552.5,616.5&gt;&gt; = 8.615648184164108

* Wcircumflex (U+0174): B&lt;&lt;789.5,216.5&gt;-&lt;795.0,184.0&gt;-&lt;798.0,163.0&gt;&gt;/B&lt;&lt;798.0,163.0&gt;-&lt;799.0,180.0&gt;-&lt;804.0,213.0&gt;&gt; = 11.496563017585768

* Wcircumflex (U+0174): L&lt;&lt;175.0,858.0&gt;--&lt;278.0,387.0&gt;&gt;/B&lt;&lt;278.0,387.0&gt;-&lt;277.0,395.0&gt;-&lt;280.5,378.5&gt;&gt; = 5.210443006962688

* Wdieresis (U+1E84): B&lt;&lt;313.5,203.5&gt;-&lt;318.0,175.0&gt;-&lt;318.0,163.0&gt;&gt;/B&lt;&lt;318.0,163.0&gt;-&lt;321.0,221.0&gt;-&lt;333.5,280.5&gt;&gt; = 2.9609361341637563

* Wdieresis (U+1E84): B&lt;&lt;522.0,456.5&gt;-&lt;519.0,442.0&gt;-&lt;520.0,451.0&gt;&gt;/L&lt;&lt;520.0,451.0&gt;--&lt;414.0,0.0&gt;&gt; = 6.886165327021434

* Wdieresis (U+1E84): B&lt;&lt;569.5,581.0&gt;-&lt;562.0,620.0&gt;-&lt;557.0,653.0&gt;&gt;/B&lt;&lt;557.0,653.0&gt;-&lt;557.0,643.0&gt;-&lt;552.5,616.5&gt;&gt; = 8.615648184164108

* Wdieresis (U+1E84): B&lt;&lt;789.5,216.5&gt;-&lt;795.0,184.0&gt;-&lt;798.0,163.0&gt;&gt;/B&lt;&lt;798.0,163.0&gt;-&lt;799.0,180.0&gt;-&lt;804.0,213.0&gt;&gt; = 11.496563017585768

* Wdieresis (U+1E84): L&lt;&lt;175.0,858.0&gt;--&lt;278.0,387.0&gt;&gt;/B&lt;&lt;278.0,387.0&gt;-&lt;277.0,395.0&gt;-&lt;280.5,378.5&gt;&gt; = 5.210443006962688

* Wgrave (U+1E80): B&lt;&lt;313.5,203.5&gt;-&lt;318.0,175.0&gt;-&lt;318.0,163.0&gt;&gt;/B&lt;&lt;318.0,163.0&gt;-&lt;321.0,221.0&gt;-&lt;333.5,280.5&gt;&gt; = 2.9609361341637563

* Wgrave (U+1E80): B&lt;&lt;522.0,456.5&gt;-&lt;519.0,442.0&gt;-&lt;520.0,451.0&gt;&gt;/L&lt;&lt;520.0,451.0&gt;--&lt;414.0,0.0&gt;&gt; = 6.886165327021434

* Wgrave (U+1E80): B&lt;&lt;569.5,581.0&gt;-&lt;562.0,620.0&gt;-&lt;557.0,653.0&gt;&gt;/B&lt;&lt;557.0,653.0&gt;-&lt;557.0,643.0&gt;-&lt;552.5,616.5&gt;&gt; = 8.615648184164108

* Wgrave (U+1E80): B&lt;&lt;789.5,216.5&gt;-&lt;795.0,184.0&gt;-&lt;798.0,163.0&gt;&gt;/B&lt;&lt;798.0,163.0&gt;-&lt;799.0,180.0&gt;-&lt;804.0,213.0&gt;&gt; = 11.496563017585768

* Wgrave (U+1E80): L&lt;&lt;175.0,858.0&gt;--&lt;278.0,387.0&gt;&gt;/B&lt;&lt;278.0,387.0&gt;-&lt;277.0,395.0&gt;-&lt;280.5,378.5&gt;&gt; = 5.210443006962688

* u1E7F6 (U+1E7F6): B&lt;&lt;105.5,449.5&gt;-&lt;124.0,521.0&gt;-&lt;160.0,576.0&gt;&gt;/L&lt;&lt;160.0,576.0&gt;--&lt;158.0,574.0&gt;&gt; = 11.79342968491043

* uni2DD4 (U+2DD4): B&lt;&lt;137.5,861.5&gt;-&lt;145.0,860.0&gt;-&lt;153.0,858.0&gt;&gt;/B&lt;&lt;153.0,858.0&gt;-&lt;147.0,861.0&gt;-&lt;142.0,865.0&gt;&gt; = 12.528807709151492
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* dagger (U+2020): L&lt;&lt;271.0,422.0&gt;--&lt;272.0,702.0&gt;&gt;

* dagger (U+2020): L&lt;&lt;361.0,703.0&gt;--&lt;362.0,424.0&gt;&gt;

* dagger (U+2020): L&lt;&lt;363.0,338.0&gt;--&lt;362.0,-275.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.777x (1777)</p>
 [code: bad-hhea-range]



</div>
</details>
</div>
</details>

<details><summary>[18] Menbere-SemiBold.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>tcaron uses component uni030C.</p>
 [code: wrong-mark]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+0265: LATIN SMALL LETTER TURNED H</td>
<td align="left">U+A78D: LATIN CAPITAL LETTER TURNED H</td>
</tr>
<tr>
<td align="left">U+026F: LATIN SMALL LETTER TURNED M</td>
<td align="left">U+019C: LATIN CAPITAL LETTER TURNED M</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Name table records must not have trailing spaces. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name table record with key = (3, 1, 1033, 9) has trailing spaces that must be removed: ' Aleme Tadesse '</p>
 [code: trailing-space]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to J</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ha_Latn (Hausa)</td>
<td align="left">Shaper didn't attach tildecomb to r</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to R</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE4</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yo_Latn (Yoruba)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB9</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bm_Latn (Bambara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dyu_Latn (Dyula)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lg_Latn (Ganda)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set.</p>
 [code: missing]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2024 The Menbere project authors&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: guillemotleft	Contours detected: 1	Expected: 2

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: Ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: Uhungarumlaut	Contours detected: 2	Expected: 3

- Glyph name: uhungarumlaut	Contours detected: 2	Expected: 3

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni01C2	Contours detected: 3	Expected: 1

- Glyph name: uni01EA	Contours detected: 3	Expected: 2

- Glyph name: uni01EB	Contours detected: 3	Expected: 2

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni0200	Contours detected: 3	Expected: 4

- Glyph name: uni0201	Contours detected: 3	Expected: 4

- Glyph name: uni0204	Contours detected: 2	Expected: 3

- Glyph name: uni0205	Contours detected: 3	Expected: 4

- Glyph name: uni0208	Contours detected: 2	Expected: 3

- Glyph name: uni0209	Contours detected: 2	Expected: 3

- Glyph name: uni020C	Contours detected: 3	Expected: 4

- Glyph name: uni020D	Contours detected: 3	Expected: 4

- Glyph name: uni0214	Contours detected: 2	Expected: 3

- Glyph name: uni0215	Contours detected: 2	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: hungarumlaut	Contours detected: 1	Expected: 2

- Glyph name: uni030B	Contours detected: 1	Expected: 2

- Glyph name: uni030F	Contours detected: 1	Expected: 2

- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

- Glyph name: Ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: Uhungarumlaut	Contours detected: 2	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: guillemotleft	Contours detected: 1	Expected: 2

- Glyph name: hungarumlaut	Contours detected: 1	Expected: 2

- Glyph name: ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: uhungarumlaut	Contours detected: 2	Expected: 3

- Glyph name: uni01C2	Contours detected: 3	Expected: 1

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: uni030B	Contours detected: 1	Expected: 2

- Glyph name: uni030F	Contours detected: 1	Expected: 2

- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 660 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 656:
equal</p>
<p>Width = 627:
plusminus, approxequal</p>
<p>Width = 499:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Dcroat.001

- overscorecomb
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, coptic, malayalam, duployan, tai-le, syriac, tifinagh, math, old-permic, canadian-aboriginal, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: duployan, cherokee, syriac</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+032F COMBINING INVERTED BREVE BELOW: try adding math</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: math, cherokee, syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: sunuwar, caucasian-albanian, thai, syriac, gothic, tifinagh, cherokee</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EAD LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EC6 LATIN CAPITAL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EC7 LATIN SMALL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ED8 LATIN CAPITAL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ED9 LATIN SMALL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2116 NUMERO SIGN: try adding cyrillic</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols</li>
<li>U+2195 UP DOWN ARROW: try adding one of: math, symbols</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: mahajani, caucasian-albanian, rejang, warang-citi, limbu, masaram-gondi, telugu, canadian-aboriginal, khojki, yi, kannada, malayalam, kharoshthi, tai-le, math, ahom, newa, takri, miao, new-tai-lue, syriac, siddham, duployan, tifinagh, armenian, thai, gujarati, khmer, saurashtra, khudawadi, elbasan, adlam, psalter-pahlavi, gunjala-gondi, meetei-mayek, mende-kikakui, dogra, zanabazar-square, tamil, tai-tham, tirhuta, symbols, hanunoo, batak, lepcha, oriya, bhaiksuki, tagalog, gurmukhi, mongolian, sharada, javanese, wancho, sinhala, hebrew, myanmar, pahawh-hmong, sogdian, devanagari, chakma, syloti-nagri, buhid, nko, bengali, tagbanwa, modi, mandaic, lao, osage, balinese, music, marchen, kaithi, brahmi, kayah-li, buginese, tibetan, soyombo, phags-pa, bassa-vah, coptic, manichaean, thaana, hanifi-rohingya, sundanese, cham, grantha, old-permic, tai-viet</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>ethiopic</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ḭ̀ ḭ́ ḭ̂ ḭ̃ ḭ̄ ḭ̆ ḭ̇ ḭ̈ ḭ̊ ḭ̋ ḭ̌ ḭ̏ ḭ̑ ḭ̒ į̆ į̇ į̈ į̊ į̋ į̏</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Makaa (Latn, 221,000 speakers), Ekpeye (Latn, 226,000 speakers), Cicipu (Latn, 44,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ma’di (Latn, 584,000 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Basaa (Latn, 332,940 speakers), Avokaya (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Fur (Latn, 1,230,163 speakers), Sar (Latn, 500,000 speakers), Dii (Latn, 71,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Nzakara (Latn, 50,000 speakers), Bafut (Latn, 158,146 speakers), Ejagham (Latn, 120,000 speakers), Mfumte (Latn, 79,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Kom (Latn, 360,685 speakers), Koonzime (Latn, 40,000 speakers), South Central Banda (Latn, 244,000 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Vute (Latn, 21,000 speakers), Mango (Latn, 77,000 speakers), Aghem (Latn, 38,843 speakers), Southern Kisi (Latn, 360,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Navajo (Latn, 166,319 speakers), Heiltsuk (Latn, 300 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Han (Latn, 6 speakers), Gulay (Latn, 250,478 speakers), Dutch (Latn, 31,709,104 speakers), Yala (Latn, 200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* W (U+0057): B&lt;&lt;305.0,191.5&gt;-&lt;309.0,166.0&gt;-&lt;310.0,152.0&gt;&gt;/B&lt;&lt;310.0,152.0&gt;-&lt;313.0,192.0&gt;-&lt;320.0,232.0&gt;&gt; = 8.374770108793845

* W (U+0057): B&lt;&lt;560.0,618.0&gt;-&lt;553.0,655.0&gt;-&lt;549.0,677.0&gt;&gt;/B&lt;&lt;549.0,677.0&gt;-&lt;549.0,668.0&gt;-&lt;545.5,646.0&gt;&gt; = 10.304846468766044

* Wacute (U+1E82): B&lt;&lt;305.0,191.5&gt;-&lt;309.0,166.0&gt;-&lt;310.0,152.0&gt;&gt;/B&lt;&lt;310.0,152.0&gt;-&lt;313.0,192.0&gt;-&lt;320.0,232.0&gt;&gt; = 8.374770108793845

* Wacute (U+1E82): B&lt;&lt;560.0,618.0&gt;-&lt;553.0,655.0&gt;-&lt;549.0,677.0&gt;&gt;/B&lt;&lt;549.0,677.0&gt;-&lt;549.0,668.0&gt;-&lt;545.5,646.0&gt;&gt; = 10.304846468766044

* Wcircumflex (U+0174): B&lt;&lt;305.0,191.5&gt;-&lt;309.0,166.0&gt;-&lt;310.0,152.0&gt;&gt;/B&lt;&lt;310.0,152.0&gt;-&lt;313.0,192.0&gt;-&lt;320.0,232.0&gt;&gt; = 8.374770108793845

* Wcircumflex (U+0174): B&lt;&lt;560.0,618.0&gt;-&lt;553.0,655.0&gt;-&lt;549.0,677.0&gt;&gt;/B&lt;&lt;549.0,677.0&gt;-&lt;549.0,668.0&gt;-&lt;545.5,646.0&gt;&gt; = 10.304846468766044

* Wdieresis (U+1E84): B&lt;&lt;305.0,191.5&gt;-&lt;309.0,166.0&gt;-&lt;310.0,152.0&gt;&gt;/B&lt;&lt;310.0,152.0&gt;-&lt;313.0,192.0&gt;-&lt;320.0,232.0&gt;&gt; = 8.374770108793845

* Wdieresis (U+1E84): B&lt;&lt;560.0,618.0&gt;-&lt;553.0,655.0&gt;-&lt;549.0,677.0&gt;&gt;/B&lt;&lt;549.0,677.0&gt;-&lt;549.0,668.0&gt;-&lt;545.5,646.0&gt;&gt; = 10.304846468766044

* Wgrave (U+1E80): B&lt;&lt;305.0,191.5&gt;-&lt;309.0,166.0&gt;-&lt;310.0,152.0&gt;&gt;/B&lt;&lt;310.0,152.0&gt;-&lt;313.0,192.0&gt;-&lt;320.0,232.0&gt;&gt; = 8.374770108793845

* Wgrave (U+1E80): B&lt;&lt;560.0,618.0&gt;-&lt;553.0,655.0&gt;-&lt;549.0,677.0&gt;&gt;/B&lt;&lt;549.0,677.0&gt;-&lt;549.0,668.0&gt;-&lt;545.5,646.0&gt;&gt; = 10.304846468766044
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* dagger (U+2020): L&lt;&lt;271.0,422.0&gt;--&lt;272.0,702.0&gt;&gt;

* dagger (U+2020): L&lt;&lt;361.0,703.0&gt;--&lt;362.0,424.0&gt;&gt;

* dagger (U+2020): L&lt;&lt;363.0,338.0&gt;--&lt;362.0,-275.0&gt;&gt;

* integral (U+222B): L&lt;&lt;297.0,694.0&gt;--&lt;296.0,0.0&gt;&gt;

* uni0199 (U+0199): L&lt;&lt;246.0,694.0&gt;--&lt;247.0,486.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.777x (1777)</p>
 [code: bad-hhea-range]



</div>
</details>
</div>
</details>

<details><summary>[18] Menbere-Medium.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>tcaron uses component uni030C.</p>
 [code: wrong-mark]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+0265: LATIN SMALL LETTER TURNED H</td>
<td align="left">U+A78D: LATIN CAPITAL LETTER TURNED H</td>
</tr>
<tr>
<td align="left">U+026F: LATIN SMALL LETTER TURNED M</td>
<td align="left">U+019C: LATIN CAPITAL LETTER TURNED M</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Name table records must not have trailing spaces. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name table record with key = (3, 1, 1033, 9) has trailing spaces that must be removed: ' Aleme Tadesse '</p>
 [code: trailing-space]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to J</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ha_Latn (Hausa)</td>
<td align="left">Shaper didn't attach tildecomb to r</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to R</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE4</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yo_Latn (Yoruba)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB9</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bm_Latn (Bambara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dyu_Latn (Dyula)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lg_Latn (Ganda)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set.</p>
 [code: missing]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2024 The Menbere project authors&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: guillemotleft	Contours detected: 1	Expected: 2

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: Ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: Uhungarumlaut	Contours detected: 2	Expected: 3

- Glyph name: uhungarumlaut	Contours detected: 2	Expected: 3

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni01C2	Contours detected: 3	Expected: 1

- Glyph name: uni01EA	Contours detected: 3	Expected: 2

- Glyph name: uni01EB	Contours detected: 3	Expected: 2

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni0200	Contours detected: 3	Expected: 4

- Glyph name: uni0201	Contours detected: 3	Expected: 4

- Glyph name: uni0204	Contours detected: 2	Expected: 3

- Glyph name: uni0205	Contours detected: 3	Expected: 4

- Glyph name: uni0208	Contours detected: 2	Expected: 3

- Glyph name: uni0209	Contours detected: 2	Expected: 3

- Glyph name: uni020C	Contours detected: 3	Expected: 4

- Glyph name: uni020D	Contours detected: 3	Expected: 4

- Glyph name: uni0214	Contours detected: 2	Expected: 3

- Glyph name: uni0215	Contours detected: 2	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: hungarumlaut	Contours detected: 1	Expected: 2

- Glyph name: uni030B	Contours detected: 1	Expected: 2

- Glyph name: uni030F	Contours detected: 1	Expected: 2

- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

- Glyph name: Ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: Uhungarumlaut	Contours detected: 2	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: guillemotleft	Contours detected: 1	Expected: 2

- Glyph name: hungarumlaut	Contours detected: 1	Expected: 2

- Glyph name: ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: uhungarumlaut	Contours detected: 2	Expected: 3

- Glyph name: uni01C2	Contours detected: 3	Expected: 1

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: uni030B	Contours detected: 1	Expected: 2

- Glyph name: uni030F	Contours detected: 1	Expected: 2

- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 660 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 656:
equal</p>
<p>Width = 627:
plusminus, approxequal</p>
<p>Width = 494:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Dcroat.001

- overscorecomb
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, coptic, malayalam, duployan, tai-le, syriac, tifinagh, math, old-permic, canadian-aboriginal, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: duployan, cherokee, syriac</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+032F COMBINING INVERTED BREVE BELOW: try adding math</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: math, cherokee, syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: sunuwar, caucasian-albanian, thai, syriac, gothic, tifinagh, cherokee</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EAD LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EC6 LATIN CAPITAL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EC7 LATIN SMALL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ED8 LATIN CAPITAL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ED9 LATIN SMALL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2116 NUMERO SIGN: try adding cyrillic</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols</li>
<li>U+2195 UP DOWN ARROW: try adding one of: math, symbols</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: mahajani, caucasian-albanian, rejang, warang-citi, limbu, masaram-gondi, telugu, canadian-aboriginal, khojki, yi, kannada, malayalam, kharoshthi, tai-le, math, ahom, newa, takri, miao, new-tai-lue, syriac, siddham, duployan, tifinagh, armenian, thai, gujarati, khmer, saurashtra, khudawadi, elbasan, adlam, psalter-pahlavi, gunjala-gondi, meetei-mayek, mende-kikakui, dogra, zanabazar-square, tamil, tai-tham, tirhuta, symbols, hanunoo, batak, lepcha, oriya, bhaiksuki, tagalog, gurmukhi, mongolian, sharada, javanese, wancho, sinhala, hebrew, myanmar, pahawh-hmong, sogdian, devanagari, chakma, syloti-nagri, buhid, nko, bengali, tagbanwa, modi, mandaic, lao, osage, balinese, music, marchen, kaithi, brahmi, kayah-li, buginese, tibetan, soyombo, phags-pa, bassa-vah, coptic, manichaean, thaana, hanifi-rohingya, sundanese, cham, grantha, old-permic, tai-viet</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>ethiopic</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ḭ̀ ḭ́ ḭ̂ ḭ̃ ḭ̄ ḭ̆ ḭ̇ ḭ̈ ḭ̊ ḭ̋ ḭ̌ ḭ̏ ḭ̑ ḭ̒ į̆ į̇ į̈ į̊ į̋ į̏</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Makaa (Latn, 221,000 speakers), Ekpeye (Latn, 226,000 speakers), Cicipu (Latn, 44,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ma’di (Latn, 584,000 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Basaa (Latn, 332,940 speakers), Avokaya (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Fur (Latn, 1,230,163 speakers), Sar (Latn, 500,000 speakers), Dii (Latn, 71,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Nzakara (Latn, 50,000 speakers), Bafut (Latn, 158,146 speakers), Ejagham (Latn, 120,000 speakers), Mfumte (Latn, 79,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Kom (Latn, 360,685 speakers), Koonzime (Latn, 40,000 speakers), South Central Banda (Latn, 244,000 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Vute (Latn, 21,000 speakers), Mango (Latn, 77,000 speakers), Aghem (Latn, 38,843 speakers), Southern Kisi (Latn, 360,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Navajo (Latn, 166,319 speakers), Heiltsuk (Latn, 300 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Han (Latn, 6 speakers), Gulay (Latn, 250,478 speakers), Dutch (Latn, 31,709,104 speakers), Yala (Latn, 200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Ohungarumlaut (U+0150): B&lt;&lt;373.0,1013.0&gt;-&lt;377.0,1018.0&gt;-&lt;381.0,1024.0&gt;&gt;/B&lt;&lt;381.0,1024.0&gt;-&lt;365.0,1009.0&gt;-&lt;351.0,997.0&gt;&gt; = 13.157542740014811

* Uhungarumlaut (U+0170): B&lt;&lt;348.0,1013.0&gt;-&lt;352.0,1018.0&gt;-&lt;356.0,1024.0&gt;&gt;/B&lt;&lt;356.0,1024.0&gt;-&lt;340.0,1009.0&gt;-&lt;326.0,997.0&gt;&gt; = 13.157542740014811

* W (U+0057): B&lt;&lt;295.0,192.0&gt;-&lt;300.0,163.0&gt;-&lt;303.0,142.0&gt;&gt;/B&lt;&lt;303.0,142.0&gt;-&lt;307.0,182.0&gt;-&lt;314.0,223.0&gt;&gt; = 13.840695491655614

* Wacute (U+1E82): B&lt;&lt;295.0,192.0&gt;-&lt;300.0,163.0&gt;-&lt;303.0,142.0&gt;&gt;/B&lt;&lt;303.0,142.0&gt;-&lt;307.0,182.0&gt;-&lt;314.0,223.0&gt;&gt; = 13.840695491655614

* Wcircumflex (U+0174): B&lt;&lt;295.0,192.0&gt;-&lt;300.0,163.0&gt;-&lt;303.0,142.0&gt;&gt;/B&lt;&lt;303.0,142.0&gt;-&lt;307.0,182.0&gt;-&lt;314.0,223.0&gt;&gt; = 13.840695491655614

* Wdieresis (U+1E84): B&lt;&lt;295.0,192.0&gt;-&lt;300.0,163.0&gt;-&lt;303.0,142.0&gt;&gt;/B&lt;&lt;303.0,142.0&gt;-&lt;307.0,182.0&gt;-&lt;314.0,223.0&gt;&gt; = 13.840695491655614

* Wgrave (U+1E80): B&lt;&lt;295.0,192.0&gt;-&lt;300.0,163.0&gt;-&lt;303.0,142.0&gt;&gt;/B&lt;&lt;303.0,142.0&gt;-&lt;307.0,182.0&gt;-&lt;314.0,223.0&gt;&gt; = 13.840695491655614

* hungarumlaut (U+02DD): B&lt;&lt;219.0,807.0&gt;-&lt;223.0,812.0&gt;-&lt;227.0,818.0&gt;&gt;/B&lt;&lt;227.0,818.0&gt;-&lt;211.0,803.0&gt;-&lt;197.0,791.0&gt;&gt; = 13.157542740014811

* ohungarumlaut (U+0151): B&lt;&lt;272.0,807.0&gt;-&lt;276.0,812.0&gt;-&lt;280.0,818.0&gt;&gt;/B&lt;&lt;280.0,818.0&gt;-&lt;264.0,803.0&gt;-&lt;250.0,791.0&gt;&gt; = 13.157542740014811

* uhungarumlaut (U+0171): B&lt;&lt;287.0,799.0&gt;-&lt;291.0,804.0&gt;-&lt;295.0,810.0&gt;&gt;/B&lt;&lt;295.0,810.0&gt;-&lt;279.0,795.0&gt;-&lt;265.0,783.0&gt;&gt; = 13.157542740014811

* uni030B (U+030B): B&lt;&lt;219.0,807.0&gt;-&lt;223.0,812.0&gt;-&lt;227.0,818.0&gt;&gt;/B&lt;&lt;227.0,818.0&gt;-&lt;211.0,803.0&gt;-&lt;197.0,791.0&gt;&gt; = 13.157542740014811
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* dagger (U+2020): L&lt;&lt;271.0,422.0&gt;--&lt;272.0,702.0&gt;&gt;

* dagger (U+2020): L&lt;&lt;361.0,703.0&gt;--&lt;362.0,424.0&gt;&gt;

* dagger (U+2020): L&lt;&lt;363.0,338.0&gt;--&lt;362.0,-275.0&gt;&gt;

* florin (U+0192): L&lt;&lt;256.0,547.0&gt;--&lt;255.0,0.0&gt;&gt;

* integral (U+222B): L&lt;&lt;267.0,692.0&gt;--&lt;265.0,0.0&gt;&gt;

* uni0199 (U+0199): L&lt;&lt;93.0,0.0&gt;--&lt;92.0,695.0&gt;&gt;

* uni0253 (U+0253): L&lt;&lt;93.0,0.0&gt;--&lt;92.0,695.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.777x (1777)</p>
 [code: bad-hhea-range]



</div>
</details>
</div>
</details>

<details><summary>[18] Menbere-ExtraLight.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>tcaron uses component uni030C.</p>
 [code: wrong-mark]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+0265: LATIN SMALL LETTER TURNED H</td>
<td align="left">U+A78D: LATIN CAPITAL LETTER TURNED H</td>
</tr>
<tr>
<td align="left">U+026F: LATIN SMALL LETTER TURNED M</td>
<td align="left">U+019C: LATIN CAPITAL LETTER TURNED M</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Name table records must not have trailing spaces. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name table record with key = (3, 1, 1033, 9) has trailing spaces that must be removed: ' Aleme Tadesse '</p>
 [code: trailing-space]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to J</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ha_Latn (Hausa)</td>
<td align="left">Shaper didn't attach tildecomb to r</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to R</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE4</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yo_Latn (Yoruba)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB9</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bm_Latn (Bambara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dyu_Latn (Dyula)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lg_Latn (Ganda)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set.</p>
 [code: missing]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2024 The Menbere project authors&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: quotedbl	Contours detected: 1	Expected: 2

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: Ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: Uhungarumlaut	Contours detected: 2	Expected: 3

- Glyph name: uhungarumlaut	Contours detected: 2	Expected: 3

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni01C2	Contours detected: 3	Expected: 1

- Glyph name: uni01EA	Contours detected: 3	Expected: 2

- Glyph name: uni01EB	Contours detected: 3	Expected: 2

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: hungarumlaut	Contours detected: 1	Expected: 2

- Glyph name: uni030B	Contours detected: 1	Expected: 2

- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

- Glyph name: Ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: Uhungarumlaut	Contours detected: 2	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hungarumlaut	Contours detected: 1	Expected: 2

- Glyph name: ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: quotedbl	Contours detected: 1	Expected: 2

- Glyph name: uhungarumlaut	Contours detected: 2	Expected: 3

- Glyph name: uni01C2	Contours detected: 3	Expected: 1

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: uni030B	Contours detected: 1	Expected: 2

- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 659 among a set of 5 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 656:
equal</p>
<p>Width = 639:
logicalnot</p>
<p>Width = 649:
plusminus, approxequal</p>
<p>Width = 491:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Dcroat.001

- overscorecomb
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, coptic, malayalam, duployan, tai-le, syriac, tifinagh, math, old-permic, canadian-aboriginal, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: duployan, cherokee, syriac</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+032F COMBINING INVERTED BREVE BELOW: try adding math</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: math, cherokee, syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: sunuwar, caucasian-albanian, thai, syriac, gothic, tifinagh, cherokee</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EAD LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EC6 LATIN CAPITAL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EC7 LATIN SMALL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ED8 LATIN CAPITAL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ED9 LATIN SMALL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2116 NUMERO SIGN: try adding cyrillic</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols</li>
<li>U+2195 UP DOWN ARROW: try adding one of: math, symbols</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: mahajani, caucasian-albanian, rejang, warang-citi, limbu, masaram-gondi, telugu, canadian-aboriginal, khojki, yi, kannada, malayalam, kharoshthi, tai-le, math, ahom, newa, takri, miao, new-tai-lue, syriac, siddham, duployan, tifinagh, armenian, thai, gujarati, khmer, saurashtra, khudawadi, elbasan, adlam, psalter-pahlavi, gunjala-gondi, meetei-mayek, mende-kikakui, dogra, zanabazar-square, tamil, tai-tham, tirhuta, symbols, hanunoo, batak, lepcha, oriya, bhaiksuki, tagalog, gurmukhi, mongolian, sharada, javanese, wancho, sinhala, hebrew, myanmar, pahawh-hmong, sogdian, devanagari, chakma, syloti-nagri, buhid, nko, bengali, tagbanwa, modi, mandaic, lao, osage, balinese, music, marchen, kaithi, brahmi, kayah-li, buginese, tibetan, soyombo, phags-pa, bassa-vah, coptic, manichaean, thaana, hanifi-rohingya, sundanese, cham, grantha, old-permic, tai-viet</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>ethiopic</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ḭ̀ ḭ́ ḭ̂ ḭ̃ ḭ̄ ḭ̆ ḭ̇ ḭ̈ ḭ̊ ḭ̋ ḭ̌ ḭ̏ ḭ̑ ḭ̒ į̆ į̇ į̈ į̊ į̋ į̏</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Makaa (Latn, 221,000 speakers), Ekpeye (Latn, 226,000 speakers), Cicipu (Latn, 44,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ma’di (Latn, 584,000 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Basaa (Latn, 332,940 speakers), Avokaya (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Fur (Latn, 1,230,163 speakers), Sar (Latn, 500,000 speakers), Dii (Latn, 71,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Nzakara (Latn, 50,000 speakers), Bafut (Latn, 158,146 speakers), Ejagham (Latn, 120,000 speakers), Mfumte (Latn, 79,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Kom (Latn, 360,685 speakers), Koonzime (Latn, 40,000 speakers), South Central Banda (Latn, 244,000 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Vute (Latn, 21,000 speakers), Mango (Latn, 77,000 speakers), Aghem (Latn, 38,843 speakers), Southern Kisi (Latn, 360,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Navajo (Latn, 166,319 speakers), Heiltsuk (Latn, 300 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Han (Latn, 6 speakers), Gulay (Latn, 250,478 speakers), Dutch (Latn, 31,709,104 speakers), Yala (Latn, 200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Ohungarumlaut (U+0150): B&lt;&lt;375.0,1010.0&gt;-&lt;394.0,1033.0&gt;-&lt;417.0,1066.0&gt;&gt;/B&lt;&lt;417.0,1066.0&gt;-&lt;401.0,1048.0&gt;-&lt;384.0,1030.0&gt;&gt; = 6.758210991968

* Uhungarumlaut (U+0170): B&lt;&lt;348.0,1010.0&gt;-&lt;367.0,1033.0&gt;-&lt;390.0,1066.0&gt;&gt;/B&lt;&lt;390.0,1066.0&gt;-&lt;374.0,1048.0&gt;-&lt;357.0,1030.0&gt;&gt; = 6.758210991968

* hungarumlaut (U+02DD): B&lt;&lt;201.0,804.0&gt;-&lt;220.0,827.0&gt;-&lt;243.0,860.0&gt;&gt;/B&lt;&lt;243.0,860.0&gt;-&lt;227.0,842.0&gt;-&lt;210.0,824.0&gt;&gt; = 6.758210991968

* ohungarumlaut (U+0151): B&lt;&lt;273.0,804.0&gt;-&lt;292.0,827.0&gt;-&lt;315.0,860.0&gt;&gt;/B&lt;&lt;315.0,860.0&gt;-&lt;299.0,842.0&gt;-&lt;282.0,824.0&gt;&gt; = 6.758210991968

* quotedbl (U+0022): L&lt;&lt;229.0,549.0&gt;--&lt;226.0,600.0&gt;&gt;/L&lt;&lt;226.0,600.0&gt;--&lt;222.0,549.0&gt;&gt; = 7.851066672974404

* uhungarumlaut (U+0171): B&lt;&lt;279.0,788.0&gt;-&lt;298.0,811.0&gt;-&lt;321.0,844.0&gt;&gt;/B&lt;&lt;321.0,844.0&gt;-&lt;305.0,826.0&gt;-&lt;288.0,808.0&gt;&gt; = 6.758210991968

* uni030B (U+030B): B&lt;&lt;201.0,804.0&gt;-&lt;220.0,827.0&gt;-&lt;243.0,860.0&gt;&gt;/B&lt;&lt;243.0,860.0&gt;-&lt;227.0,842.0&gt;-&lt;210.0,824.0&gt;&gt; = 6.758210991968
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* dagger (U+2020): L&lt;&lt;271.0,422.0&gt;--&lt;272.0,702.0&gt;&gt;

* dagger (U+2020): L&lt;&lt;361.0,703.0&gt;--&lt;362.0,424.0&gt;&gt;

* dagger (U+2020): L&lt;&lt;363.0,338.0&gt;--&lt;362.0,-275.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.777x (1777)</p>
 [code: bad-hhea-range]



</div>
</details>
</div>
</details>

<details><summary>[18] Menbere-Light.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>tcaron uses component uni030C.</p>
 [code: wrong-mark]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+0265: LATIN SMALL LETTER TURNED H</td>
<td align="left">U+A78D: LATIN CAPITAL LETTER TURNED H</td>
</tr>
<tr>
<td align="left">U+026F: LATIN SMALL LETTER TURNED M</td>
<td align="left">U+019C: LATIN CAPITAL LETTER TURNED M</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Name table records must not have trailing spaces. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name table record with key = (3, 1, 1033, 9) has trailing spaces that must be removed: ' Aleme Tadesse '</p>
 [code: trailing-space]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to J</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ha_Latn (Hausa)</td>
<td align="left">Shaper didn't attach tildecomb to r</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to R</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE4</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yo_Latn (Yoruba)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB9</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bm_Latn (Bambara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dyu_Latn (Dyula)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lg_Latn (Ganda)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set.</p>
 [code: missing]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2024 The Menbere project authors&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: quotedbl	Contours detected: 1	Expected: 2

- Glyph name: colon	Contours detected: 1	Expected: 2

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: Ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: Uhungarumlaut	Contours detected: 2	Expected: 3

- Glyph name: uhungarumlaut	Contours detected: 2	Expected: 3

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni01C2	Contours detected: 3	Expected: 1

- Glyph name: uni01EA	Contours detected: 3	Expected: 2

- Glyph name: uni01EB	Contours detected: 3	Expected: 2

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: hungarumlaut	Contours detected: 1	Expected: 2

- Glyph name: uni030B	Contours detected: 1	Expected: 2

- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

- Glyph name: Ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: Uhungarumlaut	Contours detected: 2	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: colon	Contours detected: 1	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hungarumlaut	Contours detected: 1	Expected: 2

- Glyph name: ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: quotedbl	Contours detected: 1	Expected: 2

- Glyph name: uhungarumlaut	Contours detected: 2	Expected: 3

- Glyph name: uni01C2	Contours detected: 3	Expected: 1

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: uni030B	Contours detected: 1	Expected: 2

- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 660 among a set of 5 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 656:
equal</p>
<p>Width = 650:
logicalnot</p>
<p>Width = 638:
plusminus, approxequal</p>
<p>Width = 491:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Dcroat.001

- overscorecomb
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, coptic, malayalam, duployan, tai-le, syriac, tifinagh, math, old-permic, canadian-aboriginal, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: duployan, cherokee, syriac</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+032F COMBINING INVERTED BREVE BELOW: try adding math</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: math, cherokee, syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: sunuwar, caucasian-albanian, thai, syriac, gothic, tifinagh, cherokee</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EAD LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EC6 LATIN CAPITAL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EC7 LATIN SMALL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ED8 LATIN CAPITAL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ED9 LATIN SMALL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2116 NUMERO SIGN: try adding cyrillic</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols</li>
<li>U+2195 UP DOWN ARROW: try adding one of: math, symbols</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: mahajani, caucasian-albanian, rejang, warang-citi, limbu, masaram-gondi, telugu, canadian-aboriginal, khojki, yi, kannada, malayalam, kharoshthi, tai-le, math, ahom, newa, takri, miao, new-tai-lue, syriac, siddham, duployan, tifinagh, armenian, thai, gujarati, khmer, saurashtra, khudawadi, elbasan, adlam, psalter-pahlavi, gunjala-gondi, meetei-mayek, mende-kikakui, dogra, zanabazar-square, tamil, tai-tham, tirhuta, symbols, hanunoo, batak, lepcha, oriya, bhaiksuki, tagalog, gurmukhi, mongolian, sharada, javanese, wancho, sinhala, hebrew, myanmar, pahawh-hmong, sogdian, devanagari, chakma, syloti-nagri, buhid, nko, bengali, tagbanwa, modi, mandaic, lao, osage, balinese, music, marchen, kaithi, brahmi, kayah-li, buginese, tibetan, soyombo, phags-pa, bassa-vah, coptic, manichaean, thaana, hanifi-rohingya, sundanese, cham, grantha, old-permic, tai-viet</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>ethiopic</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ḭ̀ ḭ́ ḭ̂ ḭ̃ ḭ̄ ḭ̆ ḭ̇ ḭ̈ ḭ̊ ḭ̋ ḭ̌ ḭ̏ ḭ̑ ḭ̒ į̆ į̇ į̈ į̊ į̋ į̏</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Makaa (Latn, 221,000 speakers), Ekpeye (Latn, 226,000 speakers), Cicipu (Latn, 44,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ma’di (Latn, 584,000 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Basaa (Latn, 332,940 speakers), Avokaya (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Fur (Latn, 1,230,163 speakers), Sar (Latn, 500,000 speakers), Dii (Latn, 71,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Nzakara (Latn, 50,000 speakers), Bafut (Latn, 158,146 speakers), Ejagham (Latn, 120,000 speakers), Mfumte (Latn, 79,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Kom (Latn, 360,685 speakers), Koonzime (Latn, 40,000 speakers), South Central Banda (Latn, 244,000 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Vute (Latn, 21,000 speakers), Mango (Latn, 77,000 speakers), Aghem (Latn, 38,843 speakers), Southern Kisi (Latn, 360,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Navajo (Latn, 166,319 speakers), Heiltsuk (Latn, 300 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Han (Latn, 6 speakers), Gulay (Latn, 250,478 speakers), Dutch (Latn, 31,709,104 speakers), Yala (Latn, 200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Ohungarumlaut (U+0150): B&lt;&lt;372.0,1011.0&gt;-&lt;376.0,1016.0&gt;-&lt;380.0,1020.0&gt;&gt;/B&lt;&lt;380.0,1020.0&gt;-&lt;366.0,1008.0&gt;-&lt;354.0,997.0&gt;&gt; = 4.398705354995508

* Uhungarumlaut (U+0170): B&lt;&lt;345.0,1011.0&gt;-&lt;349.0,1016.0&gt;-&lt;353.0,1020.0&gt;&gt;/B&lt;&lt;353.0,1020.0&gt;-&lt;339.0,1008.0&gt;-&lt;327.0,997.0&gt;&gt; = 4.398705354995508

* hungarumlaut (U+02DD): B&lt;&lt;204.0,805.0&gt;-&lt;208.0,810.0&gt;-&lt;212.0,814.0&gt;&gt;/B&lt;&lt;212.0,814.0&gt;-&lt;198.0,802.0&gt;-&lt;186.0,791.0&gt;&gt; = 4.398705354995508

* ohungarumlaut (U+0151): B&lt;&lt;270.0,805.0&gt;-&lt;274.0,810.0&gt;-&lt;278.0,814.0&gt;&gt;/B&lt;&lt;278.0,814.0&gt;-&lt;264.0,802.0&gt;-&lt;252.0,791.0&gt;&gt; = 4.398705354995508

* quotedbl (U+0022): L&lt;&lt;241.0,549.0&gt;--&lt;236.0,617.0&gt;&gt;/L&lt;&lt;236.0,617.0&gt;--&lt;232.0,549.0&gt;&gt; = 7.571817665138339

* uhungarumlaut (U+0171): B&lt;&lt;279.0,792.0&gt;-&lt;283.0,797.0&gt;-&lt;287.0,801.0&gt;&gt;/B&lt;&lt;287.0,801.0&gt;-&lt;273.0,789.0&gt;-&lt;261.0,778.0&gt;&gt; = 4.398705354995508

* uni030B (U+030B): B&lt;&lt;204.0,805.0&gt;-&lt;208.0,810.0&gt;-&lt;212.0,814.0&gt;&gt;/B&lt;&lt;212.0,814.0&gt;-&lt;198.0,802.0&gt;-&lt;186.0,791.0&gt;&gt; = 4.398705354995508

* uni1210 (U+1210): B&lt;&lt;400.0,452.0&gt;-&lt;413.0,458.0&gt;-&lt;427.0,450.0&gt;&gt;/B&lt;&lt;427.0,450.0&gt;-&lt;418.0,457.0&gt;-&lt;409.0,462.0&gt;&gt; = 8.130102354155916
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* dagger (U+2020): L&lt;&lt;271.0,422.0&gt;--&lt;272.0,702.0&gt;&gt;

* dagger (U+2020): L&lt;&lt;361.0,703.0&gt;--&lt;362.0,424.0&gt;&gt;

* dagger (U+2020): L&lt;&lt;363.0,338.0&gt;--&lt;362.0,-275.0&gt;&gt;

* florin (U+0192): L&lt;&lt;226.0,566.0&gt;--&lt;225.0,0.0&gt;&gt;

* integral (U+222B): L&lt;&lt;226.0,696.0&gt;--&lt;225.0,0.0&gt;&gt;

* uni0199 (U+0199): L&lt;&lt;197.0,696.0&gt;--&lt;199.0,453.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.777x (1777)</p>
 [code: bad-hhea-range]



</div>
</details>
</div>
</details>

<details><summary>[18] Menbere-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>tcaron uses component uni030C.</p>
 [code: wrong-mark]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+0265: LATIN SMALL LETTER TURNED H</td>
<td align="left">U+A78D: LATIN CAPITAL LETTER TURNED H</td>
</tr>
<tr>
<td align="left">U+026F: LATIN SMALL LETTER TURNED M</td>
<td align="left">U+019C: LATIN CAPITAL LETTER TURNED M</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Name table records must not have trailing spaces. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name table record with key = (3, 1, 1033, 9) has trailing spaces that must be removed: ' Aleme Tadesse '</p>
 [code: trailing-space]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to J</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ha_Latn (Hausa)</td>
<td align="left">Shaper didn't attach tildecomb to r</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to R</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE4</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yo_Latn (Yoruba)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB9</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bm_Latn (Bambara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dyu_Latn (Dyula)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lg_Latn (Ganda)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set.</p>
 [code: missing]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2024 The Menbere project authors&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni01C2	Contours detected: 3	Expected: 1

- Glyph name: uni01EA	Contours detected: 3	Expected: 2

- Glyph name: uni01EB	Contours detected: 3	Expected: 2

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: uni01C2	Contours detected: 3	Expected: 1

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 660 among a set of 5 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 656:
equal</p>
<p>Width = 661:
logicalnot</p>
<p>Width = 627:
plusminus, approxequal</p>
<p>Width = 491:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Dcroat.001

- overscorecomb
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, coptic, malayalam, duployan, tai-le, syriac, tifinagh, math, old-permic, canadian-aboriginal, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: duployan, cherokee, syriac</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+032F COMBINING INVERTED BREVE BELOW: try adding math</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: math, cherokee, syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: sunuwar, caucasian-albanian, thai, syriac, gothic, tifinagh, cherokee</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EAD LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EC6 LATIN CAPITAL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EC7 LATIN SMALL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ED8 LATIN CAPITAL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ED9 LATIN SMALL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2116 NUMERO SIGN: try adding cyrillic</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols</li>
<li>U+2195 UP DOWN ARROW: try adding one of: math, symbols</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: mahajani, caucasian-albanian, rejang, warang-citi, limbu, masaram-gondi, telugu, canadian-aboriginal, khojki, yi, kannada, malayalam, kharoshthi, tai-le, math, ahom, newa, takri, miao, new-tai-lue, syriac, siddham, duployan, tifinagh, armenian, thai, gujarati, khmer, saurashtra, khudawadi, elbasan, adlam, psalter-pahlavi, gunjala-gondi, meetei-mayek, mende-kikakui, dogra, zanabazar-square, tamil, tai-tham, tirhuta, symbols, hanunoo, batak, lepcha, oriya, bhaiksuki, tagalog, gurmukhi, mongolian, sharada, javanese, wancho, sinhala, hebrew, myanmar, pahawh-hmong, sogdian, devanagari, chakma, syloti-nagri, buhid, nko, bengali, tagbanwa, modi, mandaic, lao, osage, balinese, music, marchen, kaithi, brahmi, kayah-li, buginese, tibetan, soyombo, phags-pa, bassa-vah, coptic, manichaean, thaana, hanifi-rohingya, sundanese, cham, grantha, old-permic, tai-viet</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>ethiopic</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ḭ̀ ḭ́ ḭ̂ ḭ̃ ḭ̄ ḭ̆ ḭ̇ ḭ̈ ḭ̊ ḭ̋ ḭ̌ ḭ̏ ḭ̑ ḭ̒ į̆ į̇ į̈ į̊ į̋ į̏</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Makaa (Latn, 221,000 speakers), Ekpeye (Latn, 226,000 speakers), Cicipu (Latn, 44,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ma’di (Latn, 584,000 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Basaa (Latn, 332,940 speakers), Avokaya (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Fur (Latn, 1,230,163 speakers), Sar (Latn, 500,000 speakers), Dii (Latn, 71,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Nzakara (Latn, 50,000 speakers), Bafut (Latn, 158,146 speakers), Ejagham (Latn, 120,000 speakers), Mfumte (Latn, 79,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Kom (Latn, 360,685 speakers), Koonzime (Latn, 40,000 speakers), South Central Banda (Latn, 244,000 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Vute (Latn, 21,000 speakers), Mango (Latn, 77,000 speakers), Aghem (Latn, 38,843 speakers), Southern Kisi (Latn, 360,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Navajo (Latn, 166,319 speakers), Heiltsuk (Latn, 300 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Han (Latn, 6 speakers), Gulay (Latn, 250,478 speakers), Dutch (Latn, 31,709,104 speakers), Yala (Latn, 200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* W (U+0057): B&lt;&lt;541.0,693.5&gt;-&lt;537.0,714.0&gt;-&lt;537.0,717.0&gt;&gt;/B&lt;&lt;537.0,717.0&gt;-&lt;536.0,710.0&gt;-&lt;532.0,690.0&gt;&gt; = 8.13010235415596

* Wacute (U+1E82): B&lt;&lt;541.0,693.5&gt;-&lt;537.0,714.0&gt;-&lt;537.0,717.0&gt;&gt;/B&lt;&lt;537.0,717.0&gt;-&lt;536.0,710.0&gt;-&lt;532.0,690.0&gt;&gt; = 8.13010235415596

* Wcircumflex (U+0174): B&lt;&lt;541.0,693.5&gt;-&lt;537.0,714.0&gt;-&lt;537.0,717.0&gt;&gt;/B&lt;&lt;537.0,717.0&gt;-&lt;536.0,710.0&gt;-&lt;532.0,690.0&gt;&gt; = 8.13010235415596

* Wdieresis (U+1E84): B&lt;&lt;541.0,693.5&gt;-&lt;537.0,714.0&gt;-&lt;537.0,717.0&gt;&gt;/B&lt;&lt;537.0,717.0&gt;-&lt;536.0,710.0&gt;-&lt;532.0,690.0&gt;&gt; = 8.13010235415596

* Wgrave (U+1E80): B&lt;&lt;541.0,693.5&gt;-&lt;537.0,714.0&gt;-&lt;537.0,717.0&gt;&gt;/B&lt;&lt;537.0,717.0&gt;-&lt;536.0,710.0&gt;-&lt;532.0,690.0&gt;&gt; = 8.13010235415596

* uni1226 (U+1226): B&lt;&lt;131.0,188.0&gt;-&lt;185.0,256.0&gt;-&lt;308.0,351.0&gt;&gt;/B&lt;&lt;308.0,351.0&gt;-&lt;279.0,337.0&gt;-&lt;241.0,337.0&gt;&gt; = 11.9116530000708
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* dagger (U+2020): L&lt;&lt;271.0,422.0&gt;--&lt;272.0,702.0&gt;&gt;

* dagger (U+2020): L&lt;&lt;361.0,703.0&gt;--&lt;362.0,424.0&gt;&gt;

* dagger (U+2020): L&lt;&lt;363.0,338.0&gt;--&lt;362.0,-275.0&gt;&gt;

* florin (U+0192): L&lt;&lt;242.0,557.0&gt;--&lt;240.0,0.0&gt;&gt;

* integral (U+222B): L&lt;&lt;242.0,691.0&gt;--&lt;240.0,0.0&gt;&gt;

* uni0199 (U+0199): L&lt;&lt;95.0,0.0&gt;--&lt;94.0,692.0&gt;&gt;

* uni0253 (U+0253): L&lt;&lt;95.0,0.0&gt;--&lt;94.0,692.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.777x (1777)</p>
 [code: bad-hhea-range]



</div>
</details>
</div>
</details>

<details><summary>[18] Menbere-Thin.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>tcaron uses component uni030C.</p>
 [code: wrong-mark]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+0265: LATIN SMALL LETTER TURNED H</td>
<td align="left">U+A78D: LATIN CAPITAL LETTER TURNED H</td>
</tr>
<tr>
<td align="left">U+026F: LATIN SMALL LETTER TURNED M</td>
<td align="left">U+019C: LATIN CAPITAL LETTER TURNED M</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Name table records must not have trailing spaces. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name table record with key = (3, 1, 1033, 9) has trailing spaces that must be removed: ' Aleme Tadesse '</p>
 [code: trailing-space]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to J</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ha_Latn (Hausa)</td>
<td align="left">Shaper didn't attach tildecomb to r</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to R</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECB</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE4</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yo_Latn (Yoruba)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB9</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bm_Latn (Bambara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dyu_Latn (Dyula)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lg_Latn (Ganda)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set.</p>
 [code: missing]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2024 The Menbere project authors&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni01C2	Contours detected: 3	Expected: 1

- Glyph name: uni01EA	Contours detected: 3	Expected: 2

- Glyph name: uni01EB	Contours detected: 3	Expected: 2

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: uni01C2	Contours detected: 3	Expected: 1

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 659 among a set of 7 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 656:
equal</p>
<p>Width = 629:
logicalnot</p>
<p>Width = 491:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Dcroat.001

- overscorecomb
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, coptic, malayalam, duployan, tai-le, syriac, tifinagh, math, old-permic, canadian-aboriginal, hebrew</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: duployan, cherokee, syriac</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+032F COMBINING INVERTED BREVE BELOW: try adding math</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: math, cherokee, syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: sunuwar, caucasian-albanian, thai, syriac, gothic, tifinagh, cherokee</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EAD LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EC6 LATIN CAPITAL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EC7 LATIN SMALL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ED8 LATIN CAPITAL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ED9 LATIN SMALL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2116 NUMERO SIGN: try adding cyrillic</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols</li>
<li>U+2195 UP DOWN ARROW: try adding one of: math, symbols</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: mahajani, caucasian-albanian, rejang, warang-citi, limbu, masaram-gondi, telugu, canadian-aboriginal, khojki, yi, kannada, malayalam, kharoshthi, tai-le, math, ahom, newa, takri, miao, new-tai-lue, syriac, siddham, duployan, tifinagh, armenian, thai, gujarati, khmer, saurashtra, khudawadi, elbasan, adlam, psalter-pahlavi, gunjala-gondi, meetei-mayek, mende-kikakui, dogra, zanabazar-square, tamil, tai-tham, tirhuta, symbols, hanunoo, batak, lepcha, oriya, bhaiksuki, tagalog, gurmukhi, mongolian, sharada, javanese, wancho, sinhala, hebrew, myanmar, pahawh-hmong, sogdian, devanagari, chakma, syloti-nagri, buhid, nko, bengali, tagbanwa, modi, mandaic, lao, osage, balinese, music, marchen, kaithi, brahmi, kayah-li, buginese, tibetan, soyombo, phags-pa, bassa-vah, coptic, manichaean, thaana, hanifi-rohingya, sundanese, cham, grantha, old-permic, tai-viet</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>ethiopic</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ḭ̀ ḭ́ ḭ̂ ḭ̃ ḭ̄ ḭ̆ ḭ̇ ḭ̈ ḭ̊ ḭ̋ ḭ̌ ḭ̏ ḭ̑ ḭ̒ į̆ į̇ į̈ į̊ į̋ į̏</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Makaa (Latn, 221,000 speakers), Ekpeye (Latn, 226,000 speakers), Cicipu (Latn, 44,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ma’di (Latn, 584,000 speakers), Igbo (Latn, 27,823,640 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Basaa (Latn, 332,940 speakers), Avokaya (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Fur (Latn, 1,230,163 speakers), Sar (Latn, 500,000 speakers), Dii (Latn, 71,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Nzakara (Latn, 50,000 speakers), Bafut (Latn, 158,146 speakers), Ejagham (Latn, 120,000 speakers), Mfumte (Latn, 79,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Kom (Latn, 360,685 speakers), Koonzime (Latn, 40,000 speakers), South Central Banda (Latn, 244,000 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Vute (Latn, 21,000 speakers), Mango (Latn, 77,000 speakers), Aghem (Latn, 38,843 speakers), Southern Kisi (Latn, 360,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Navajo (Latn, 166,319 speakers), Heiltsuk (Latn, 300 speakers), Ebira (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Han (Latn, 6 speakers), Gulay (Latn, 250,478 speakers), Dutch (Latn, 31,709,104 speakers), Yala (Latn, 200,000 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* uni2D87 (U+2D87): B&lt;&lt;465.5,1022.5&gt;-&lt;423.0,1020.0&gt;-&lt;382.0,1014.0&gt;&gt;/B&lt;&lt;382.0,1014.0&gt;-&lt;452.0,1008.0&gt;-&lt;491.0,968.5&gt;&gt; = 13.224742784214579

* uni2DAE (U+2DAE): B&lt;&lt;465.5,1022.5&gt;-&lt;423.0,1020.0&gt;-&lt;382.0,1014.0&gt;&gt;/B&lt;&lt;382.0,1014.0&gt;-&lt;452.0,1008.0&gt;-&lt;491.0,968.5&gt;&gt; = 13.224742784214579

* uni2DDD (U+2DDD): B&lt;&lt;615.0,895.0&gt;-&lt;584.0,856.0&gt;-&lt;531.0,844.0&gt;&gt;/B&lt;&lt;531.0,844.0&gt;-&lt;592.0,843.0&gt;-&lt;625.0,817.5&gt;&gt; = 13.696723106612248
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* dagger (U+2020): L&lt;&lt;271.0,422.0&gt;--&lt;272.0,702.0&gt;&gt;

* dagger (U+2020): L&lt;&lt;361.0,703.0&gt;--&lt;362.0,424.0&gt;&gt;

* dagger (U+2020): L&lt;&lt;363.0,338.0&gt;--&lt;362.0,-275.0&gt;&gt;

* uni0199 (U+0199): L&lt;&lt;167.0,705.0&gt;--&lt;169.0,448.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.777x (1777)</p>
 [code: bad-hhea-range]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Each font in a family must have the same set of vertical metrics values. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>usWinAscent is not the same across the family:
Menbere Bold: 1476
Menbere SemiBold: 1544
Menbere Medium: 1609
Menbere ExtraLight: 1660
Menbere Light: 1660
Menbere: 1660
Menbere Thin: 1660</p>
 [code: usWinAscent-mismatch]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 51 | 77 | 794 | 50 | 677 | 0 | 
| 0% | 0% | 3% | 5% | 48% | 3% | 41% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
