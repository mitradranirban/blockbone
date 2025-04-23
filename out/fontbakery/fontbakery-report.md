## FontBakery report

fontbakery version: 0.13.2







## Check results



<details><summary>[24] Blockbone[wght].ttf</summary>
<div>
<details>
    <summary>💥 <b>ERROR</b> Familyname must be unique according to namecheck.fontdata.com <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontdata-namecheck">fontdata_namecheck</a></summary>
    <div>







* 💥 **ERROR** <p>Failed to access: <a href="https://namecheck.fontdata.com/api/?q=Blockbone">https://namecheck.fontdata.com/api/?q=Blockbone</a>.
This check relies on the external service <a href="http://namecheck.fontdata.com">http://namecheck.fontdata.com</a> via the internet. While the service cannot be reached or does not respond this check is broken.</p>
<pre><code>	You can exclude this check with the command line option:
	-x fontdata_namecheck

	Or you can wait until the service is available again.
	If the problem persists please report this issue at: https://github.com/fonttools/fontbakery/issues

	Original error message:
	&lt;class 'requests.exceptions.ReadTimeout'&gt;
</code></pre>
 [code: namecheck-service]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Validates subfamilyNameID and postScriptNameID for the default instance record <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-varfont-valid-default-instance-nameids">opentype/varfont/valid_default_instance_nameids</a></summary>
    <div>







* 🔥 **FAIL** <p>'Regular' instance has the same coordinates as the default instance; its postscript name should be 'Blockbone-Regular', instead of 'BlockBone-Regular'.</p>
 [code: invalid-default-instance-postscript-name]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check that legacy accents aren't used in composite glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#legacy-accents">legacy_accents</a></summary>
    <div>







* 🔥 **FAIL** <p>Legacy accent &quot;hungarumlaut&quot; is defined in GDEF as a mark (class 3).</p>
 [code: legacy-accents-gdef]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>GF_TransLatin_Arabic glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to J when shaping the text 'ÍJ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to j when shaping the text 'íj́'</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_TransLatin_Arabic glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŀ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Aogonek when shaping the text 'Ą́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Aogonek when shaping the text 'Ą̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Eogonek when shaping the text 'Ę́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Eogonek when shaping the text 'Ę̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Edotaccent when shaping the text 'Ė́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Edotaccent when shaping the text 'Ė̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Idotaccent when shaping the text 'İ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Idotaccent when shaping the text 'İ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Idotaccent when shaping the text 'İ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Idotaccent when shaping the text 'İ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Idotaccent when shaping the text 'İ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Idotaccent when shaping the text 'İ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Iogonek when shaping the text 'Į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotaccentcomb to Iogonek when shaping the text 'Į̇́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to dotaccentcomb when shaping the text 'Į̇́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Iogonek when shaping the text 'Į̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotaccentcomb to Iogonek when shaping the text 'Į̇̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to dotaccentcomb when shaping the text 'Į̇̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to J when shaping the text 'J̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotaccentcomb to J when shaping the text 'J̇̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to dotaccentcomb when shaping the text 'J̇̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to L when shaping the text 'L̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to M when shaping the text 'M̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to R when shaping the text 'R̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Uogonek when shaping the text 'Ų́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Uogonek when shaping the text 'Ų̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Umacron when shaping the text 'Ū́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Umacron when shaping the text 'Ū̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to aogonek when shaping the text 'ą́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to aogonek when shaping the text 'ą̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to eogonek when shaping the text 'ę́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to eogonek when shaping the text 'ę̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to edotaccent when shaping the text 'ė́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to edotaccent when shaping the text 'ė̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotaccentcomb to i when shaping the text 'i̇́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to dotaccentcomb when shaping the text 'i̇́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotaccentcomb to i when shaping the text 'i̇̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to dotaccentcomb when shaping the text 'i̇̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotaccentcomb to i when shaping the text 'i̇̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to dotaccentcomb when shaping the text 'i̇̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotaccentcomb to iogonek when shaping the text 'į̇́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to dotaccentcomb when shaping the text 'į̇́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to iogonek when shaping the text 'į̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotaccentcomb to iogonek when shaping the text 'į̇̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to dotaccentcomb when shaping the text 'į̇̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to j when shaping the text 'j̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotaccentcomb to j when shaping the text 'j̇̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to dotaccentcomb when shaping the text 'j̇̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to l when shaping the text 'l̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to m when shaping the text 'm̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to r when shaping the text 'r̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uogonek when shaping the text 'ų́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uogonek when shaping the text 'ų̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to umacron when shaping the text 'ū́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to umacron when shaping the text 'ū̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ĳ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ĳ</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check family name for GF Guide compliance. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-family-name-compliance">googlefonts/family_name_compliance</a></summary>
    <div>







* 🔥 **FAIL** <p>&quot;BlockBone&quot; is a CamelCased name. To solve this, simply use spaces instead in the font name.</p>
 [code: camelcase]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking file is named canonically. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-canonical-filename">googlefonts/canonical_filename</a></summary>
    <div>







* 🔥 **FAIL** <p>Expected &quot;BlockBone[wght].ttf. Got Blockbone[wght].ttf.</p>
 [code: bad-filename]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-names">googlefonts/font_names</a></summary>
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
<td align="left"><strong>BlockBone Regular</strong></td>
<td align="left"><strong>BlockBone</strong></td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Regular</td>
<td align="left">Regular</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">BlockBone Regular</td>
<td align="left">BlockBone Regular</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left"><strong>Blockbone-Regular</strong></td>
<td align="left"><strong>BlockBone-Regular</strong></td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left"><strong>BlockBone</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left"><strong>Regular</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Version format is correct in 'name' table? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-version-format">googlefonts/name/version_format</a></summary>
    <div>







* 🔥 **FAIL** <p>The NameID.VERSION_STRING (nameID=5) value must follow the pattern &quot;Version X.Y&quot; with X.Y greater than or equal to 1.000. The &quot;Version &quot; prefix is a recommendation given by the OpenType spec. Current version string is: &quot;Version 0.500&quot;</p>
 [code: bad-version-strings]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-mark-chars">opentype/gdef_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), dieresiscomb (U+0308), ogonekcomb (U+0328), ringcomb (U+030A) and tildecomb (U+0303)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-non-mark-chars">opentype/gdef_non_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+00C0 and U+02DD</p>
 [code: non-mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-spacing-marks">opentype/gdef_spacing_marks</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs seem to be spacing (because they have width &gt; 0 on the hmtx table) so they may be in the GDEF mark glyph class by mistake, or they should have zero width instead:
Agrave (U+00C0) and hungarumlaut (U+02DD)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#alt-caron">alt_caron</a></summary>
    <div>









* ⚠️ **WARN** <p>Lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>dcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#gpos-kerning-info">gpos_kerning_info</a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#interpolation-issues">interpolation_issues</a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 point 78 in glyph 'Udieresis' has a kink between location wght=400 and location wght=900

- Contour 2 point 0 in glyph 'Udieresis' has a kink between location wght=400 and location wght=900

- Contour 0 point 66 in glyph 'nine' has a kink between location wght=400 and location wght=900

- Contour 1 in glyph 'Cacute': becomes underweight between wght=400 and wght=900.

- Contour 0 in glyph 'Zcaron': becomes underweight between wght=400 and wght=900.

- Contour 0 point 111 in glyph 'w' has a kink between location wght=400 and location wght=900

- Contour 1 in glyph 'Ograve': becomes underweight between wght=400 and wght=900.

- Contour 2 in glyph 'Ograve': becomes underweight between wght=400 and wght=900.

- Contour 0 in glyph 'dcroat': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'Wgrave': becomes underweight between wght=400 and wght=900.

- Contour 0 point 139 in glyph 'Wgrave' has a kink between location wght=400 and location wght=900

- Contour 0 in glyph 'aring': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'Lacute': becomes underweight between wght=400 and wght=900.

- Contour 0 in glyph 'quotesinglbase': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'Ugrave': becomes underweight between wght=400 and wght=900.

- Contour 2 in glyph 'Aacute': becomes underweight between wght=400 and wght=900.

- Contour 0 point 7 in glyph 'micro' has a kink between location wght=400 and location wght=900

- Contour 0 point 50 in glyph 'v' has a kink between location wght=400 and location wght=900

- Contour 0 in glyph 'quoteright': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'Oacute': becomes underweight between wght=400 and wght=900.

- Contour 2 in glyph 'Oacute': becomes underweight between wght=400 and wght=900.

- Contour 0 in glyph 'semicolon': becomes underweight between wght=400 and wght=900.

- Contour 0 in glyph 'zdotaccent': becomes underweight between wght=400 and wght=900.

- Contour 0 point 39 in glyph 'zdotaccent' has a kink between location wght=400 and location wght=900

- Contour 0 in glyph 'z': becomes underweight between wght=400 and wght=900.

- Contour 0 point 39 in glyph 'z' has a kink between location wght=400 and location wght=900

- Contour 0 in glyph 'germandbls': becomes underweight between wght=400 and wght=900.

- Contour 0 point 24 in glyph 'germandbls' has a kink between location wght=400 and location wght=900

- Contour 0 point 82 in glyph 'germandbls' has a kink between location wght=400 and location wght=900

- Contour 0 in glyph 'zacute': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'zacute': becomes underweight between wght=400 and wght=900.

- Contour 0 point 39 in glyph 'zacute' has a kink between location wght=400 and location wght=900

- Contour 0 in glyph 'gravecomb': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'Nacute': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'Ygrave': becomes underweight between wght=400 and wght=900.

- Contour 0 in glyph 'S': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'Wacute': becomes underweight between wght=400 and wght=900.

- Contour 0 point 139 in glyph 'Wacute' has a kink between location wght=400 and location wght=900

- Contour 0 in glyph 'Scaron': becomes underweight between wght=400 and wght=900.

- Contour 0 in glyph 'three': becomes underweight between wght=400 and wght=900.

- Contour 0 point 61 in glyph 'three' has a kink between location wght=400 and location wght=900

- Contour 0 in glyph 'dcaron': becomes underweight between wght=400 and wght=900.

- Contour 2 in glyph 'dcaron': becomes underweight between wght=400 and wght=900.

- Contour 0 start point differs in glyph 'Lslash' between location wght=400 and location wght=900

- Contour 1 in glyph 'Iacute': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'lacute': becomes underweight between wght=400 and wght=900.

- Contour 1 start point differs in glyph 'OE' between location wght=400 and location wght=900

- Contour 1 in glyph 'OE': becomes underweight between wght=400 and wght=900.

- Contour 2 start point differs in glyph 'OE' between location wght=400 and location wght=900

- Contour 1 in glyph 'Ohungarumlaut': becomes underweight between wght=400 and wght=900.

- Contour 0 in glyph 'atilde': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'iacute': becomes underweight between wght=400 and wght=900.

- Contour 0 in glyph 'Scedilla': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'Racute': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'perthousand': becomes underweight between wght=400 and wght=900.

- Contour 3 in glyph 'perthousand': becomes underweight between wght=400 and wght=900.

- Contour 5 in glyph 'perthousand': becomes underweight between wght=400 and wght=900.

- Contour 1 point 10 in glyph 'perthousand' has a kink between location wght=400 and location wght=900

- Contour 3 point 10 in glyph 'perthousand' has a kink between location wght=400 and location wght=900

- Contour 1 in glyph 'O': becomes underweight between wght=400 and wght=900.

- Contour 0 point 18 in glyph 'zero' has a kink between location wght=400 and location wght=900

- Contour 0 in glyph 'Sacute': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'Sacute': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'Uacute': becomes underweight between wght=400 and wght=900.

- Contour 0 in glyph 'a': becomes underweight between wght=400 and wght=900.

- Contour 0 point 134 in glyph 'X' has a kink between location wght=400 and location wght=900

- Contour 0 in glyph 'Zacute': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'Zacute': becomes underweight between wght=400 and wght=900.

- Contour 0 in glyph 'quoteleft': becomes underweight between wght=400 and wght=900.

- Contour 0 in glyph 'slash': becomes underweight between wght=400 and wght=900.

- Contour 0 in glyph 'grave': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'Oslash': becomes underweight between wght=400 and wght=900.

- Contour 0 point 63 in glyph 'eth' has a kink between location wght=400 and location wght=900

- Contour 0 point 44 in glyph 'yen' has a kink between location wght=400 and location wght=900

- Contour 1 in glyph 'Odieresis': becomes underweight between wght=400 and wght=900.

- Contour 3 start point differs in glyph 'Odieresis' between location wght=400 and location wght=900

- Contour 3 in glyph 'Odieresis': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'percent': becomes underweight between wght=400 and wght=900.

- Contour 3 in glyph 'percent': becomes underweight between wght=400 and wght=900.

- Contour 1 point 10 in glyph 'percent' has a kink between location wght=400 and location wght=900

- Contour 3 point 10 in glyph 'percent' has a kink between location wght=400 and location wght=900

- Contour 2 start point differs in glyph 'B' between location wght=400 and location wght=900

- Contour 2 start point differs in glyph 'Edieresis' between location wght=400 and location wght=900

- Contour 2 in glyph 'Edieresis': becomes underweight between wght=400 and wght=900.

- Contour 0 point 122 in glyph 'asterisk' has a kink between location wght=400 and location wght=900

- Contour 0 in glyph 'Agrave': becomes underweight between wght=400 and wght=900.

- Contour 0 point 139 in glyph 'W' has a kink between location wght=400 and location wght=900

- Contour 0 in glyph 'threequarters': becomes underweight between wght=400 and wght=900.

- Contour 0 point 49 in glyph 'threequarters' has a kink between location wght=400 and location wght=900

- Contour 1 in glyph 'Egrave': becomes underweight between wght=400 and wght=900.

- Contour 0 in glyph 'Z': becomes underweight between wght=400 and wght=900.

- Contour 1 start point differs in glyph 'Adieresis' between location wght=400 and location wght=900

- Contour 1 in glyph 'Adieresis': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'Eacute': becomes underweight between wght=400 and wght=900.

- Contour 0 in glyph 'acutecomb': becomes underweight between wght=400 and wght=900.

- Contour 1 in glyph 'Igrave': becomes underweight between wght=400 and wght=900.

- Contour 0 in glyph 'threesuperior': becomes underweight between wght=400 and wght=900.

- Contour 0 point 49 in glyph 'threesuperior' has a kink between location wght=400 and location wght=900

- Contour 0 in glyph 'Zdotaccent': becomes underweight between wght=400 and wght=900.

- Contour 0 in glyph 'd': becomes underweight between wght=400 and wght=900.
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#mandatory-avar-table">mandatory_avar_table</a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table. Most variable fonts should include an avar table to correctly define axes progression rates.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 550 among a set of 4 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 600:
logicalnot, equal, plusminus</p>
<p>Width = 500:
multiply, greater</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* R (U+0052): L&lt;&lt;260.0,414.0&gt;--&lt;261.0,365.0&gt;&gt; has the same coordinates as a previous segment.

* Racute (U+0154): L&lt;&lt;260.0,414.0&gt;--&lt;261.0,365.0&gt;&gt; has the same coordinates as a previous segment.

* Rcaron (U+0158): L&lt;&lt;260.0,414.0&gt;--&lt;261.0,365.0&gt;&gt; has the same coordinates as a previous segment.

* asterisk (U+002A): L&lt;&lt;270.0,329.0&gt;--&lt;270.0,329.0&gt;&gt; has the same coordinates as a previous segment.

* asterisk (U+002A): L&lt;&lt;270.0,329.0&gt;--&lt;270.0,329.0&gt;&gt; has the same coordinates as a previous segment.

* asterisk (U+002A): L&lt;&lt;270.0,329.0&gt;--&lt;270.0,329.0&gt;&gt; has the same coordinates as a previous segment.

* asterisk (U+002A): L&lt;&lt;270.0,329.0&gt;--&lt;270.0,329.0&gt;&gt; has the same coordinates as a previous segment.

* asterisk (U+002A): L&lt;&lt;270.0,329.0&gt;--&lt;270.0,329.0&gt;&gt; has the same coordinates as a previous segment.

* asterisk (U+002A): L&lt;&lt;270.0,329.0&gt;--&lt;270.0,329.0&gt;&gt; has the same coordinates as a previous segment.

* asterisk (U+002A): L&lt;&lt;270.0,329.0&gt;--&lt;270.0,329.0&gt;&gt; has the same coordinates as a previous segment.

* asterisk (U+002A): L&lt;&lt;270.0,329.0&gt;--&lt;270.0,329.0&gt;&gt; has the same coordinates as a previous segment.

* asterisk (U+002A): L&lt;&lt;270.0,329.0&gt;--&lt;270.0,329.0&gt;&gt; has the same coordinates as a previous segment.

* asterisk (U+002A): L&lt;&lt;270.0,329.0&gt;--&lt;270.0,329.0&gt;&gt; has the same coordinates as a previous segment.

* paragraph (U+00B6): B&lt;&lt;299.0,501.0&gt;-&lt;299.0,501.0&gt;-&lt;299.0,501.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- idotaccent

- periodcentered.loclCAT
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, coptic, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: hebrew, coptic, tai-le, canadian-aboriginal, syriac, duployan, old-permic, malayalam, math, tifinagh, todhri</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
<li>U+FB04 LATIN SMALL LIGATURE FFL: not included in any glyphset definition</li>
<li>U+FB05 LATIN SMALL LIGATURE LONG S T: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĩ ĭ i̇ ǐ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ ĵ j̆ j̇ j̊</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-direction">outline_direction</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* asciicircum (U+005E) has a counter-clockwise outer contour

* asciitilde (U+007E) has a counter-clockwise outer contour

* asterisk (U+002A) has a counter-clockwise outer contour

* cent (U+00A2) has a counter-clockwise outer contour

* daggerdbl (U+2021) has a counter-clockwise outer contour

* exclam (U+0021) has a counter-clockwise outer contour

* exclamdown (U+00A1) has a counter-clockwise outer contour

* question (U+003F) has a counter-clockwise outer contour

* questiondown (U+00BF) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 1 | 0 | 7 | 16 | 89 | 8 | 115 | 0 | 
| 0% | 0% | 3% | 7% | 38% | 3% | 49% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
