# X-SAMPA and IPA Converter

As used in https://neonnaut.neocities.org/ipa-keyboard

### Additional notation

To enable X-SAMPA users to convert to the IPA without limitations, or just to make some things easier, some additional notations that are not standard in X-SAMPA have been added:

| Extras     | Standard     | IPA     | Description                       |
|------------|--------------|---------|-----------------------------------|
| p\_!   | O\\      | ʘ   | labial click                  |
| d\_!   | \|\\     | ǀ   | dental click                  |
| t\_!   | !\\      | !   | (post)alveolar click          |
| l\_!   | \|\\\|\\ | ǁ   | alveolar lateral click        |
| c\_!   | =\\      | ǂ   | palatoalveolar click          |
| t\`\_! |              | 𝼊   | retroflex click               |
| i\\    | 1        | ɨ   | close central unrounded vowel |
| u\\    | }        | ʉ   | close central rounded vowel   |
| b\\    |              | ⱱ   | voiced labiodental flap       |
| g\\    |              | ɡ   | opentail letter g             |
| )      |              | ◌͡◌ | tie above                     |
| (      |              | ◌͜◌ | tie below                     |
| \_f    |              | ◌͎  | whistled                      |
| \_i    |              | ◌↓  | ingressive                    |
| \_s    |              | ◌͍  | spread lips                   |
| \_V    |              | ◌͈  | tenseness                     |
| \_W    |              | ◌͉  | weak articulation             |
| \_z    |              | ◌͊  | denasalisation                |

A backslash `\` is used to move diacritics to a non-default position. For example `m_0` gives `m̥` while `m_0\` gives `m̊`.

A backslash `\` is also used to turn tone diacritics into Chao letters. For example `a_H` gives `á` while `a_H\` gives `a˦`.

A plus sign `+` is used before a character to make it superscript. For example `+a` gives `ᵃ`. It only works for some letters that have a superscript form in Unicode. For numbers except for 6, 8 and 9, it forms a superscript number. For example `+1` gives `¹`.
