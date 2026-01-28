<hr>

<h2>Scope</h2>
<p>
Arruppadai is a Unicode-native digital epigraphy platform focused on the
encoding, representation, and scholarly use of <strong>Tamil-Brahmi</strong>
inscriptions. The project prioritizes accuracy, transparency, and long-term
digital preservation over visual approximation or font-specific rendering.
</p>

<p>
This repository serves as a foundational release, establishing a minimal,
standards-compliant base upon which tools for transcription, comparison,
annotation, and publication can be built.
</p>

<h2>Unicode Commitment</h2>
<p>
Arruppadai strictly adheres to the official Unicode encoding for the
Brahmi script block (<code>U+11000–U+1107F</code>), including Tamil-Brahmi
variants as encoded by the Unicode Consortium.
</p>

<p>
All textual representations in this project are stored and processed as
Unicode code points rather than glyph substitutions or private-use mappings.
This ensures interoperability across platforms, future-proofing, and
scholarly verifiability.
</p>

<p>
No legacy fonts, image-based encodings, or non-standard transliteration-only
representations are used as authoritative data.
</p>

<h2>Scholarly Intent</h2>
<p>
Arruppadai is designed to support academic and research use cases, including:
</p>

<ul>
  <li>Digital epigraphy and inscriptional studies</li>
  <li>Historical linguistics and script evolution research</li>
  <li>Unicode-based textual analysis</li>
  <li>Reproducible citation and digital publication</li>
</ul>

<p>
The project does not attempt to impose interpretive readings or linguistic
reconstructions. Instead, it provides a neutral, standards-aligned digital
substrate upon which such work may be conducted.
</p>

<h2>Citation</h2>
<p>
If you reference or build upon this project, please cite it as:
</p>

<blockquote>
Ārruppaṭai. <em>A Unicode-native digital epigraphy platform for Tamil-Brahmi</em>.
Version 1.0 (Foundational Release). GitHub, 2026.
</blockquote>

<p>
Persistent identifiers (DOI) and formal archival references will be added in
subsequent releases.
</p>
<hr>

<h2>Unicode Tamil-Brahmi Samples</h2>
<p>
The following examples demonstrate direct usage of the official Unicode
Brahmi block for Tamil-Brahmi textual representation. All characters shown
below are encoded using standard Unicode code points and rendered using
Unicode-compliant fonts.
</p>

<h3>Vowels (Uyir)</h3>
<table border="1" cellpadding="6" cellspacing="0">
  <tr>
    <th>Character</th>
    <th>Unicode</th>
    <th>Transliteration</th>
  </tr>
  <tr><td style="font-size:1.5em;">𑀅</td><td>U+11005</td><td>a</td></tr>
  <tr><td style="font-size:1.5em;">𑀆</td><td>U+11006</td><td>ā</td></tr>
  <tr><td style="font-size:1.5em;">𑀇</td><td>U+11007</td><td>i</td></tr>
  <tr><td style="font-size:1.5em;">𑀉</td><td>U+11009</td><td>u</td></tr>
  <tr><td style="font-size:1.5em;">𑀋</td><td>U+1100B</td><td>e</td></tr>
  <tr><td style="font-size:1.5em;">𑀍</td><td>U+1100D</td><td>ai</td></tr>
</table>

<h3>Consonants (Mei)</h3>
<table border="1" cellpadding="6" cellspacing="0">
  <tr>
    <th>Character</th>
    <th>Unicode</th>
    <th>Transliteration</th>
  </tr>
  <tr><td style="font-size:1.5em;">𑀓</td><td>U+11013</td><td>k</td></tr>
  <tr><td style="font-size:1.5em;">𑀢</td><td>U+11022</td><td>t</td></tr>
  <tr><td style="font-size:1.5em;">𑀧</td><td>U+11027</td><td>p</td></tr>
  <tr><td style="font-size:1.5em;">𑀫</td><td>U+1102B</td><td>m</td></tr>
  <tr><td style="font-size:1.5em;">𑀮</td><td>U+1102E</td><td>l</td></tr>
  <tr><td style="font-size:1.5em;">𑀵</td><td>U+11035</td><td>ḻ (zh)</td></tr>
</table>

<h3>Example Word Forms</h3>
<table border="1" cellpadding="6" cellspacing="0">
  <tr>
    <th>Unicode Text</th>
    <th>Transliteration</th>
    <th>Notes</th>
  </tr>
  <tr>
    <td style="font-size:1.5em;">𑀢𑀫𑀺𑀮</td>
    <td>tamiḻ</td>
    <td>Classical ethnonym / language name</td>
  </tr>
  <tr>
    <td style="font-size:1.5em;">𑀓𑁇𑀢𑀮</td>
    <td>kōtal</td>
    <td>Demonstrates vowel markers</td>
  </tr>
</table>

<p>
These examples are intended to illustrate direct Unicode usage rather than
to assert specific epigraphical readings. Interpretive, palaeographic, and
chronological analyses remain outside the scope of this foundational release.
</p>
