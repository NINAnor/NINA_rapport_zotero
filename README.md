# NINA_rapport_zotero
Zotero stil fil for NINA rapporter

## Utgangspunkt
csl-filen bygger på APA stil, versjon 6:
https://editor.citationstyles.org/styleInfo/?styleId=http%3A%2F%2Fwww.zotero.org%2Fstyles%2Fapa


## Behov for tilpassninger
Stilen for NINA rapporter er noe individell og har tilpassninger der NINA synes det hensiktsmessig.
Eksempler for NINA stilen finnes her: https://nina.sharepoint.com/sites/intranett/SitePages/nn_bibl_Guide-to-authors.aspx

Har du ønsker om endringer eller ytterlige tilpasninger, nye kildetyper eller lignende,
opprett saker her: https://github.com/NINAnor/NINA_rapport_zotero/issues

## Lisens
Det brukes samme lisens som stilen den er basert på:
Creative Commons Attribution-ShareAlike 3.0 License

## Installasjon  i Zotero
Go to "Preferences...", "Cite", "Styles", click the "+" button and select the downloaded style.

## Endre filen
1. Klon dette repository (`git clone https://github.com/NINAnor/NINA_rapport_zotero.git`)
2. Opprett ny "branch" for endringer (f.eks. `git checkout -b artikkel_referanser`) 
3. Last csl-filen opp til i Online editoren: https://editor.citationstyles.org/visualEditor/ Veileder til den grafiske online editoren finnes her: https://github.com/citation-style-language/csl-editor/wiki/User-guide-for-the-CSL-Editor
4. Endre stilen
5. Last ned endret stilen og lagre den samme sted
6. Last opp ny versjon til github
   - `git diff` for å sjekke endringene
   - `git commit -m "fjernet komma bak journal" norsk-institutt-for-naturforskning-rapport.csl` for å bekrefte at endringene er riktig å kommentere på dem
   - `git push origin artikkel_referanser` for å laste endringene opp til github
7. Opprett Pull request på: https://github.com/NINAnor/NINA_rapport_zotero
8. Godta pull request og slet branch om alt er som det skal
