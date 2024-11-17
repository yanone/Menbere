## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[22] Menbere2020B-Bold.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Description strings in the name table must not contain copyright info. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Some namerecords with ID=10 (NameID.DESCRIPTION) containing copyright info should be removed (perhaps these were added by a longstanding FontLab Studio 5.x bug that copied copyright notices to them.)</p>
 [code: copyright-on-description]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 244, but got 222 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoLineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: OS/2]



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
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoLineGap (100) and hhea lineGap (0) must be equal.</p>
 [code: lineGap]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Space and non-breaking space have the same width? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Space and non-breaking space have differing width: The space glyph named space is 420 font units wide, non-breaking space named (uni00A0) is 325 font units wide, and both should be positive and the same. GlyphsApp has &quot;Sidebearing arithmetic&quot; (<a href="https://glyphsapp.com/tutorials/spacing">https://glyphsapp.com/tutorials/spacing</a>) which allows you to set the non-breaking space width to always equal the space width.</p>
 [code: different-widths]



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
<p>&quot;Copyright (c) 2020 by Aleme Tadesse. All rights reserved.&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left"><strong>Menbere2020B Bold</strong></td>
<td align="left"><strong>Menbere2020B</strong></td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Bold</td>
<td align="left">Bold</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Menbere2020B Bold</td>
<td align="left">Menbere2020B Bold</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left">Menbere2020B-Bold</td>
<td align="left">Menbere2020B-Bold</td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left"><strong>Menbere2020B</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left"><strong>Bold</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x00A1 (INVERTED EXCLAMATION MARK)


- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x0300 (COMBINING GRAVE ACCENT)


- 0x0301 (COMBINING ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0303 (COMBINING TILDE)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x0307 (COMBINING DOT ABOVE)


- 0x0308 (COMBINING DIAERESIS)


- 0x030A (COMBINING RING ABOVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


- 0x0328 (COMBINING OGONEK)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;100&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



* 🔥 **FAIL** <p>The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 776 when it should be at least 1200</p>
 [code: bad-hhea-range]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: C	Contours detected: 2	Expected: 1

- Glyph name: E	Contours detected: 2	Expected: 1

- Glyph name: F	Contours detected: 2	Expected: 1

- Glyph name: G	Contours detected: 2	Expected: 1

- Glyph name: H	Contours detected: 2	Expected: 1

- Glyph name: I	Contours detected: 2	Expected: 1

- Glyph name: J	Contours detected: 2	Expected: 1

- Glyph name: L	Contours detected: 2	Expected: 1

- Glyph name: M	Contours detected: 2	Expected: 1

- Glyph name: N	Contours detected: 2	Expected: 1

- Glyph name: S	Contours detected: 2	Expected: 1

- Glyph name: T	Contours detected: 2	Expected: 1

- Glyph name: U	Contours detected: 2	Expected: 1

- Glyph name: V	Contours detected: 2	Expected: 1

- Glyph name: X	Contours detected: 2	Expected: 1

- Glyph name: Y	Contours detected: 2	Expected: 1

- Glyph name: Z	Contours detected: 2	Expected: 1

- Glyph name: grave	Contours detected: 2	Expected: 1

- Glyph name: c	Contours detected: 2	Expected: 1

- Glyph name: f	Contours detected: 2	Expected: 1

- Glyph name: h	Contours detected: 2	Expected: 1

- Glyph name: l	Contours detected: 2	Expected: 1

- Glyph name: m	Contours detected: 2	Expected: 1

- Glyph name: n	Contours detected: 2	Expected: 1

- Glyph name: r	Contours detected: 2	Expected: 1

- Glyph name: s	Contours detected: 2	Expected: 1

- Glyph name: t	Contours detected: 2	Expected: 1

- Glyph name: u	Contours detected: 2	Expected: 1

- Glyph name: v	Contours detected: 2	Expected: 1

- Glyph name: w	Contours detected: 2	Expected: 1

- Glyph name: x	Contours detected: 2	Expected: 1

- Glyph name: y	Contours detected: 2	Expected: 1

- Glyph name: z	Contours detected: 2	Expected: 1

- Glyph name: uni00AD	Contours detected: 1	Expected: 0

- Glyph name: macron	Contours detected: 2	Expected: 1

- Glyph name: uni00B2	Contours detected: 2	Expected: 1

- Glyph name: uni00B3	Contours detected: 2	Expected: 1

- Glyph name: acute	Contours detected: 2	Expected: 1

- Glyph name: uni00B5	Contours detected: 2	Expected: 1

- Glyph name: cedilla	Contours detected: 2	Expected: 1

- Glyph name: uni00B9	Contours detected: 2	Expected: 1

- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: threequarters	Contours detected: 2	Expected: 3 or 4

- Glyph name: Agrave	Contours detected: 2	Expected: 3

- Glyph name: Aacute	Contours detected: 2	Expected: 3

- Glyph name: Acircumflex	Contours detected: 2	Expected: 3

- Glyph name: Atilde	Contours detected: 2	Expected: 3

- Glyph name: Adieresis	Contours detected: 2	Expected: 4

- Glyph name: Aring	Contours detected: 2	Expected: 3 or 4

- Glyph name: Edieresis	Contours detected: 2	Expected: 3

- Glyph name: Idieresis	Contours detected: 2	Expected: 3

- Glyph name: Ograve	Contours detected: 2	Expected: 3

- Glyph name: Oacute	Contours detected: 2	Expected: 3

- Glyph name: Ocircumflex	Contours detected: 2	Expected: 3

- Glyph name: Otilde	Contours detected: 2	Expected: 3

- Glyph name: Odieresis	Contours detected: 2	Expected: 4

- Glyph name: Udieresis	Contours detected: 2	Expected: 3

- Glyph name: germandbls	Contours detected: 2	Expected: 1

- Glyph name: agrave	Contours detected: 2	Expected: 3

- Glyph name: aacute	Contours detected: 2	Expected: 3

- Glyph name: acircumflex	Contours detected: 2	Expected: 3

- Glyph name: atilde	Contours detected: 2	Expected: 3

- Glyph name: adieresis	Contours detected: 2	Expected: 4

- Glyph name: aring	Contours detected: 2	Expected: 4

- Glyph name: ae	Contours detected: 2	Expected: 3

- Glyph name: egrave	Contours detected: 2	Expected: 3

- Glyph name: eacute	Contours detected: 2	Expected: 3

- Glyph name: ecircumflex	Contours detected: 2	Expected: 3

- Glyph name: edieresis	Contours detected: 2	Expected: 4

- Glyph name: idieresis	Contours detected: 2	Expected: 3

- Glyph name: ograve	Contours detected: 2	Expected: 3

- Glyph name: oacute	Contours detected: 2	Expected: 3

- Glyph name: ocircumflex	Contours detected: 2	Expected: 3

- Glyph name: otilde	Contours detected: 2	Expected: 3

- Glyph name: odieresis	Contours detected: 2	Expected: 4

- Glyph name: oslash	Contours detected: 2	Expected: 3

- Glyph name: udieresis	Contours detected: 2	Expected: 3

- Glyph name: ydieresis	Contours detected: 2	Expected: 3

- Glyph name: dotlessi	Contours detected: 2	Expected: 1

- Glyph name: Lslash	Contours detected: 2	Expected: 1

- Glyph name: lslash	Contours detected: 2	Expected: 1

- Glyph name: oe	Contours detected: 2	Expected: 3

- Glyph name: Ydieresis	Contours detected: 2	Expected: 3

- Glyph name: florin	Contours detected: 2	Expected: 1

- Glyph name: circumflex	Contours detected: 2	Expected: 1

- Glyph name: caron	Contours detected: 2	Expected: 1

- Glyph name: breve	Contours detected: 2	Expected: 1

- Glyph name: dotaccent	Contours detected: 2	Expected: 1

- Glyph name: ogonek	Contours detected: 2	Expected: 1

- Glyph name: tilde	Contours detected: 2	Expected: 1

- Glyph name: pi	Contours detected: 2	Expected: 1

- Glyph name: quotesinglbase	Contours detected: 2	Expected: 1

- Glyph name: perthousand	Contours detected: 2	Expected: 6 or 7

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: uni2126	Contours detected: 2	Expected: 1

- Glyph name: product	Contours detected: 2	Expected: 1

- Glyph name: summation	Contours detected: 2	Expected: 1

- Glyph name: integral	Contours detected: 2	Expected: 1

- Glyph name: Aacute	Contours detected: 2	Expected: 3

- Glyph name: Acircumflex	Contours detected: 2	Expected: 3

- Glyph name: Adieresis	Contours detected: 2	Expected: 4

- Glyph name: Agrave	Contours detected: 2	Expected: 3

- Glyph name: Aring	Contours detected: 2	Expected: 3 or 4

- Glyph name: Atilde	Contours detected: 2	Expected: 3

- Glyph name: C	Contours detected: 2	Expected: 1

- Glyph name: E	Contours detected: 2	Expected: 1

- Glyph name: Edieresis	Contours detected: 2	Expected: 3

- Glyph name: F	Contours detected: 2	Expected: 1

- Glyph name: G	Contours detected: 2	Expected: 1

- Glyph name: H	Contours detected: 2	Expected: 1

- Glyph name: I	Contours detected: 2	Expected: 1

- Glyph name: Idieresis	Contours detected: 2	Expected: 3

- Glyph name: J	Contours detected: 2	Expected: 1

- Glyph name: L	Contours detected: 2	Expected: 1

- Glyph name: Lslash	Contours detected: 2	Expected: 1

- Glyph name: M	Contours detected: 2	Expected: 1

- Glyph name: N	Contours detected: 2	Expected: 1

- Glyph name: Oacute	Contours detected: 2	Expected: 3

- Glyph name: Ocircumflex	Contours detected: 2	Expected: 3

- Glyph name: Odieresis	Contours detected: 2	Expected: 4

- Glyph name: Ograve	Contours detected: 2	Expected: 3

- Glyph name: Otilde	Contours detected: 2	Expected: 3

- Glyph name: S	Contours detected: 2	Expected: 1

- Glyph name: T	Contours detected: 2	Expected: 1

- Glyph name: U	Contours detected: 2	Expected: 1

- Glyph name: Udieresis	Contours detected: 2	Expected: 3

- Glyph name: V	Contours detected: 2	Expected: 1

- Glyph name: X	Contours detected: 2	Expected: 1

- Glyph name: Y	Contours detected: 2	Expected: 1

- Glyph name: Ydieresis	Contours detected: 2	Expected: 3

- Glyph name: Z	Contours detected: 2	Expected: 1

- Glyph name: aacute	Contours detected: 2	Expected: 3

- Glyph name: acircumflex	Contours detected: 2	Expected: 3

- Glyph name: acute	Contours detected: 2	Expected: 1

- Glyph name: adieresis	Contours detected: 2	Expected: 4

- Glyph name: ae	Contours detected: 2	Expected: 3

- Glyph name: agrave	Contours detected: 2	Expected: 3

- Glyph name: aring	Contours detected: 2	Expected: 4

- Glyph name: atilde	Contours detected: 2	Expected: 3

- Glyph name: breve	Contours detected: 2	Expected: 1

- Glyph name: c	Contours detected: 2	Expected: 1

- Glyph name: caron	Contours detected: 2	Expected: 1

- Glyph name: cedilla	Contours detected: 2	Expected: 1

- Glyph name: circumflex	Contours detected: 2	Expected: 1

- Glyph name: dotaccent	Contours detected: 2	Expected: 1

- Glyph name: dotlessi	Contours detected: 2	Expected: 1

- Glyph name: eacute	Contours detected: 2	Expected: 3

- Glyph name: ecircumflex	Contours detected: 2	Expected: 3

- Glyph name: edieresis	Contours detected: 2	Expected: 4

- Glyph name: egrave	Contours detected: 2	Expected: 3

- Glyph name: f	Contours detected: 2	Expected: 1

- Glyph name: fi	Contours detected: 2	Expected: 3

- Glyph name: fraction	Contours detected: 2	Expected: 1

- Glyph name: germandbls	Contours detected: 2	Expected: 1

- Glyph name: grave	Contours detected: 2	Expected: 1

- Glyph name: h	Contours detected: 2	Expected: 1

- Glyph name: idieresis	Contours detected: 2	Expected: 3

- Glyph name: integral	Contours detected: 2	Expected: 1

- Glyph name: l	Contours detected: 2	Expected: 1

- Glyph name: lslash	Contours detected: 2	Expected: 1

- Glyph name: m	Contours detected: 2	Expected: 1

- Glyph name: macron	Contours detected: 2	Expected: 1

- Glyph name: n	Contours detected: 2	Expected: 1

- Glyph name: oacute	Contours detected: 2	Expected: 3

- Glyph name: ocircumflex	Contours detected: 2	Expected: 3

- Glyph name: odieresis	Contours detected: 2	Expected: 4

- Glyph name: oe	Contours detected: 2	Expected: 3

- Glyph name: ogonek	Contours detected: 2	Expected: 1

- Glyph name: ograve	Contours detected: 2	Expected: 3

- Glyph name: onehalf	Contours detected: 2	Expected: 3

- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

- Glyph name: oslash	Contours detected: 2	Expected: 3

- Glyph name: otilde	Contours detected: 2	Expected: 3

- Glyph name: perthousand	Contours detected: 2	Expected: 6 or 7

- Glyph name: pi	Contours detected: 2	Expected: 1

- Glyph name: product	Contours detected: 2	Expected: 1

- Glyph name: quotesinglbase	Contours detected: 2	Expected: 1

- Glyph name: r	Contours detected: 2	Expected: 1

- Glyph name: s	Contours detected: 2	Expected: 1

- Glyph name: summation	Contours detected: 2	Expected: 1

- Glyph name: t	Contours detected: 2	Expected: 1

- Glyph name: threequarters	Contours detected: 2	Expected: 3 or 4

- Glyph name: tilde	Contours detected: 2	Expected: 1

- Glyph name: u	Contours detected: 2	Expected: 1

- Glyph name: udieresis	Contours detected: 2	Expected: 3

- Glyph name: uni00AD	Contours detected: 1	Expected: 0

- Glyph name: uni00B5	Contours detected: 2	Expected: 1

- Glyph name: uni2126	Contours detected: 2	Expected: 1

- Glyph name: v	Contours detected: 2	Expected: 1

- Glyph name: w	Contours detected: 2	Expected: 1

- Glyph name: x	Contours detected: 2	Expected: 1

- Glyph name: y	Contours detected: 2	Expected: 1

- Glyph name: ydieresis	Contours detected: 2	Expected: 3

- Glyph name: z	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 534 among a set of 12 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 450:
plus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Euro.001

- _401
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
<li>U+0008 : try adding symbols</li>
<li>U+0009 : try adding symbols</li>
<li>U+001D : try adding one of: balinese, symbols</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: math, greek, yi</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+F8FF : not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>ethiopic</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* uni2DD2 (U+2DD2): B&lt;&lt;106.5,648.0&gt;-&lt;113.0,647.0&gt;-&lt;120.0,645.0&gt;&gt;/B&lt;&lt;120.0,645.0&gt;-&lt;113.0,649.0&gt;-&lt;106.0,653.5&gt;&gt; = 13.799485396019362
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* bar (U+007C): L&lt;&lt;88.0,510.0&gt;--&lt;89.0,0.0&gt;&gt;

* dollar (U+0024): L&lt;&lt;232.0,67.0&gt;--&lt;233.0,255.0&gt;&gt;

* greaterequal (U+2265): L&lt;&lt;487.0,-95.0&gt;--&lt;46.0,-94.0&gt;&gt;

* notequal (U+2260): L&lt;&lt;48.0,196.0&gt;--&lt;217.0,195.0&gt;&gt;

* plusminus (U+00B1): L&lt;&lt;225.0,253.0&gt;--&lt;224.0,415.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Does font file include unacceptable control character glyphs? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following unacceptable control characters were identified:
fonts/ttf/Menbere2020B-Bold.ttf: uni0009</p>
 [code: unacceptable]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 13 | 10 | 120 | 7 | 101 | 0 | 
| 0% | 0% | 5% | 4% | 48% | 3% | 40% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
