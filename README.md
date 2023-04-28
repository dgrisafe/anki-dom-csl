# anki-dom-csl

Create a custom [Citation Style Language (CSL)](https://citationstyles.org/) that will work with Anki html files.

I want the citation titles to be html <a> tags that will be clickable in Anki cards.

# Template by A. Cromba

I used as a template [A minimal citation style (for grant proposals)](https://anton.cromba.ch/2016/02/07/a-minimal-citation-stylefor-grant-proposals/) by Anton Cromba.

# `Cmd`+`Shift`+`C` for Quick Copy in Zotero

Press `Cmd`+`Shift`+`C` while highlighting one or more references in Zotero to "Quick Copy" them to the clipboard.

Then paste from the clipboard into the References field of Anki (in the html field).

This will create a clean format for references, which may be consistently used across cards.

# Escape Characters in XML

How to learn [Escape Characters in XML](https://stackoverflow.com/questions/1091945/what-characters-do-i-need-to-escape-in-xml-documents) so html tags can be automatically incorporated into quick copy.

|character|code|
|--|--|
|`"`|`&quot;`|
|`'`|`&apos;`|
|`<`|`&lt;`|
|`>`|`&gt;`|
|`&`|`&amp;`|

# Examples

Note, some examples have URL links that hyperlink while others do not, but they all show in a similar format.

Blum, D. <a href="https://www.nytimes.com/2023/02/24/well/eat/ozempic-side-effects-alcohol.html">Some People on Ozempic Lose the Desire to Drink. Scientists Are Asking Why.</a> The New York Times (2023)

Gandhi, M. et al. in (2023)

Walter, K. Fentanyl Overdose JAMA 329, 184 (2023)

Peachman, R. R. Will the New CDC Opioid Prescribing Guidelines Help Correct the Course in Pain Care? JAMA 329, 111–113 (2023)

## Raw HTML

This is how the above addresses appear without html

```
Blum, D. <a href="https://www.nytimes.com/2023/02/24/well/eat/ozempic-side-effects-alcohol.html">Some People on Ozempic Lose the Desire to Drink. Scientists Are Asking Why.</a> The New York Times (2023)

Gandhi, M. et al. in (2023)

Walter, K. Fentanyl Overdose JAMA 329, 184 (2023)

Peachman, R. R. Will the New CDC Opioid Prescribing Guidelines Help Correct the Course in Pain Care? JAMA 329, 111–113 (2023)
```
