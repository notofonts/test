## FontBakery report

fontbakery version: 0.12.10



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSerifTest[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoAscender value should be greater than 931, but got 800 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[16] NotoSerifTest[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 240, but got 200 instead</p>
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
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (800) and hhea ascent (1000) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Space and non-breaking space have the same width? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Space and non-breaking space have differing width: The space glyph named space is 200 font units wide, non-breaking space named (uni00A0) is 260 font units wide, and both should be positive and the same. GlyphsApp has &quot;Sidebearing arithmetic&quot; (<a href="https://glyphsapp.com/tutorials/spacing">https://glyphsapp.com/tutorials/spacing</a>) which allows you to set the non-breaking space width to always equal the space width.</p>
 [code: different-widths]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2022 Google Inc. All Rights Reserved.&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;200&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 579:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSerifTest/googlefonts/variable-ttf does not have an article.</p>
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
<li>U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, tifinagh, old-permic, malayalam, syriac, tai-le, math, canadian-aboriginal</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0E70 : not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
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
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Fur (Latn, 1,230,163 speakers), Dan (Latn, 1,099,244 speakers), Ekpeye (Latn, 226,000 speakers), Makaa (Latn, 221,000 speakers), Vute (Latn, 21,000 speakers), Avokaya (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Nateni (Latn, 100,000 speakers), Mundani (Latn, 34,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ngbaka (Latn, 1,020,000 speakers), Bafut (Latn, 158,146 speakers), Dii (Latn, 71,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Yala (Latn, 200,000 speakers), Nzakara (Latn, 50,000 speakers), Ebira (Latn, 2,200,000 speakers), Navajo (Latn, 166,319 speakers), Southern Kisi (Latn, 360,000 speakers), Basaa (Latn, 332,940 speakers), South Central Banda (Latn, 244,000 speakers), Kom (Latn, 360,685 speakers), Aghem (Latn, 38,843 speakers), Igbo (Latn, 27,823,640 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Mango (Latn, 77,000 speakers), Zapotec (Latn, 490,000 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Mfumte (Latn, 79,000 speakers), Lugbara (Latn, 2,200,000 speakers), Sar (Latn, 500,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* uni0E70 (U+0E70): X=428.0,Y=2.0 (should be at baseline 0?)

* uni0E70 (U+0E70): X=428.0,Y=2.0 (should be at baseline 0?)

* uni0E70 (U+0E70): X=898.0,Y=2.0 (should be at baseline 0?)

* uni0E70 (U+0E70): X=898.0,Y=2.0 (should be at baseline 0?)

* uni0E70 (U+0E70): X=740.0,Y=1.0 (should be at baseline 0?)

* uni0E70 (U+0E70): X=570.0,Y=1.0 (should be at baseline 0?)

* uni0E70 (U+0E70): X=162.0,Y=-1.5 (should be at baseline 0?)

* uni0E70 (U+0E70): X=128.0,Y=1.0 (should be at baseline 0?)

* uni0E70 (U+0E70): X=128.0,Y=1.0 (should be at baseline 0?)

* Cdotaccent (U+010A): X=375.0,Y=801.0 (should be at ascender 800?)

* Cdotaccent (U+010A): X=375.0,Y=801.0 (should be at ascender 800?)

* Edotaccent (U+0116): X=281.5,Y=801.0 (should be at ascender 800?)

* Edotaccent (U+0116): X=362.0,Y=801.0 (should be at ascender 800?)

* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?)

* uni0122 (U+0122): X=519.0,Y=1.5 (should be at baseline 0?)

* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at baseline 0?)

* Gdotaccent (U+0120): X=403.0,Y=801.0 (should be at ascender 800?)

* Gdotaccent (U+0120): X=403.0,Y=801.0 (should be at ascender 800?)

* Idotaccent (U+0130): X=183.0,Y=801.0 (should be at ascender 800?)

* Idotaccent (U+0130): X=183.0,Y=801.0 (should be at ascender 800?)

* Zdotaccent (U+017B): X=311.0,Y=801.0 (should be at ascender 800?)

* Zdotaccent (U+017B): X=311.0,Y=801.0 (should be at ascender 800?)

* asterisk (U+002A): X=76.0,Y=698.0 (should be at cap-height 700?)

* c (U+0063): X=426.0,Y=501.5 (should be at x-height 500?)

* cdotaccent (U+010B): X=226.0,Y=698.0 (should be at cap-height 700?)

* cdotaccent (U+010B): X=340.0,Y=698.0 (should be at cap-height 700?)

* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

* dcaron (U+010F): X=655.0,Y=702.0 (should be at cap-height 700?)

* dotaccent (U+02D9): X=40.0,Y=698.0 (should be at cap-height 700?)

* dotaccent (U+02D9): X=154.0,Y=698.0 (should be at cap-height 700?)

* uni0307 (U+0307): X=-57.0,Y=698.0 (should be at cap-height 700?)

* uni0307 (U+0307): X=57.0,Y=698.0 (should be at cap-height 700?)

* edotaccent (U+0117): X=218.0,Y=698.0 (should be at cap-height 700?)

* edotaccent (U+0117): X=332.0,Y=698.0 (should be at cap-height 700?)

* eight (U+0038): X=160.5,Y=698.5 (should be at cap-height 700?)

* eogonek (U+0119): X=266.5,Y=-198.5 (should be at descender -200?)

* f (U+0066): X=343.0,Y=699.0 (should be at cap-height 700?)

* g (U+0067): X=75.0,Y=-201.5 (should be at descender -200?)

* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

* gbreve (U+011F): X=75.0,Y=-201.5 (should be at descender -200?)

* gbreve (U+011F): X=161.0,Y=-0.5 (should be at baseline 0?)

* uni0123 (U+0123): X=75.0,Y=-201.5 (should be at descender -200?)

* uni0123 (U+0123): X=161.0,Y=-0.5 (should be at baseline 0?)

* gdotaccent (U+0121): X=75.0,Y=-201.5 (should be at descender -200?)

* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at baseline 0?)

* gdotaccent (U+0121): X=199.0,Y=698.0 (should be at cap-height 700?)

* gdotaccent (U+0121): X=313.0,Y=698.0 (should be at cap-height 700?)

* h (U+0068): X=481.5,Y=499.5 (should be at x-height 500?)

* i (U+0069): X=104.0,Y=698.0 (should be at cap-height 700?)

* i (U+0069): X=218.0,Y=698.0 (should be at cap-height 700?)

* iogonek (U+012F): X=104.0,Y=698.0 (should be at cap-height 700?)

* iogonek (U+012F): X=218.0,Y=698.0 (should be at cap-height 700?)

* j (U+006A): X=94.0,Y=698.0 (should be at cap-height 700?)

* j (U+006A): X=208.0,Y=698.0 (should be at cap-height 700?)

* lacute (U+013A): X=143.0,Y=799.0 (should be at ascender 800?)

* lacute (U+013A): X=105.0,Y=799.0 (should be at ascender 800?)

* lcaron (U+013E): X=351.0,Y=702.0 (should be at cap-height 700?)

* m (U+006D): X=794.0,Y=499.5 (should be at x-height 500?)

* n (U+006E): X=492.5,Y=499.5 (should be at x-height 500?)

* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

* p (U+0070): X=18.0,Y=-198.0 (should be at descender -200?)

* p (U+0070): X=26.0,Y=-198.0 (should be at descender -200?)

* p (U+0070): X=284.0,Y=-198.0 (should be at descender -200?)

* p (U+0070): X=287.0,Y=-198.0 (should be at descender -200?)

* q (U+0071): X=297.0,Y=-198.0 (should be at descender -200?)

* q (U+0071): X=330.0,Y=-198.0 (should be at descender -200?)

* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

* q (U+0071): X=588.0,Y=-198.0 (should be at descender -200?)

* q (U+0071): X=596.0,Y=-198.0 (should be at descender -200?)

* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at baseline 0?)

* quotedblright (U+201D): X=270.5,Y=699.0 (should be at cap-height 700?)

* quotedblright (U+201D): X=70.5,Y=699.0 (should be at cap-height 700?)

* quoteright (U+2019): X=70.5,Y=699.0 (should be at cap-height 700?)

* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at baseline 0?)

* s (U+0073): X=228.0,Y=499.0 (should be at x-height 500?)

* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

* tcaron (U+0165): X=354.0,Y=702.0 (should be at cap-height 700?)

* thorn (U+00FE): X=18.0,Y=-198.0 (should be at descender -200?)

* thorn (U+00FE): X=26.0,Y=-198.0 (should be at descender -200?)

* thorn (U+00FE): X=284.0,Y=-198.0 (should be at descender -200?)

* thorn (U+00FE): X=287.0,Y=-198.0 (should be at descender -200?)

* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

* zdotaccent (U+017C): X=209.0,Y=698.0 (should be at cap-height 700?)

* zdotaccent (U+017C): X=323.0,Y=698.0 (should be at cap-height 700?)

* caroncommaaccent: X=290.0,Y=702.0 (should be at cap-height 700?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTest/googlefonts/variable-ttf/NotoSerifTest[wght].ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 9 | 9 | 97 | 7 | 129 | 0 | 
| 0% | 0% | 4% | 4% | 39% | 3% | 51% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
