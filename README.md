# Tanakh — dansk gengivelse (selah-da)

Dette er en dansk gengivelse af den hebraiske Tanakh. Hvert vers ligger i
sin egen fil, og hvert dansk ord står **over for sit eget hebraiske ord** —
én række ord for ord, og én løbende tekst at læse.

**Skrift: latinsk med æ ø å.** Teksten er skrevet på dansk retskrivning.

> **Denne tekst er lavet af en maskine, og den venter på et dansk øre.**
> Hvor dansken er klodset, stiv eller ikke er sådan, folk faktisk taler og
> skriver — **skal den rettes.** Ved siden af hvert ord står hebraisk, så du
> selv kan se efter.

Men **læs `CONTRIBUTING.md`, før du retter noget.** Nogle ting, der ligner
fejl, er valg, og de bliver forklaret der.

---

## Filernes form

```
<bog>/<kapitel>/<vers>.json
```

Hver fil:

```json
{
  "translation": "verset som løbende tekst",
  "tokens": [{"surface": "hebraisk ord", "gloss": "dansk betydning"}]
}
```

`surface` — det hebraiske vidnesbyrd. Det er ikke vores at skrive; det kommer
fra originalen og ændres ikke.

`gloss` — den danske betydning af **netop dette** hebraiske ord. Antallet af
glosser er lig med antallet af hebraiske ord. Altid.

`translation` — det samme vers læst i sammenhæng, så det kan læses højt.

Begge sider kommer fra det samme hebraiske vers, og **hvor de ikke stemmer
overens, er det værd at melde.**

## Hvad tegnene ⟨ ⟩ betyder

De bruges til to ting, og det er vigtigt at holde dem ude fra hinanden.

**1 · ⟨את⟩ — et hebraisk tegn, der ikke oversættes.** Ordet את står foran
sætningens genstand. Dansk har intet ord for det, og derfor står det, som det
er skrevet. Det er ikke en trykfejl; det er et ord, der faktisk står i
teksten.

> I begyndelsen skabte Elohim ⟨את⟩ himlene og ⟨את⟩ jorden. — 1 Mos 1,1

**2 · ⟨ord⟩ — dansk, som hebraisk ikke har.** Hebraisk udelader ofte verbet
*at være*. Hvor dansken har brug for det, for at sætningen kan holde, står det
inden for tegnene. Tegnene siger: *dette ord har oversætteren tilføjet; det
står ikke i hebraisk.*

> Hør, Jisrael: Jahve ⟨er⟩ vor Elohim, Jahve ⟨er⟩ én. — 5 Mos 6,4

**Inden for tegnene står aldrig et fremmed sprog.** Inde i ⟨ ⟩ står dansk
eller det hebraiske tegn — intet tredje.

## Navnet

Guds Navn **oversættes ikke; det translittereres.**

| hebraisk | her | hvad vi har afvist på Navnets plads |
|---|---|---|
| יהוה | **Jahve** | **HERREN**, **Herren**, **Herre**, **Gud**, **Jehova**, **Den Evige** |
| יה | **Jah** | — |
| אלהים | **Elohim** | **Gud** på Elohims plads |
| אל | **El** | — |
| אלוה | **Eloah** | — |
| אדני (om Gud) | **Adonaj** | **Herren**, **Herre Gud** |
| שדי | **Shaddaj** | *Den Almægtige* som eneste gengivelse |
| יהוה צבאות | **Jahve Tsevaot** — intet imellem | *Hærskarers HERRE* |

> En salme af David. Jahve er min hyrde, jeg mangler intet. — Sl 23,1

**HERREN** er den form, mange danske læsere kender. Alligevel står den ikke
her. Den er en oversættelse af en *titel*, ikke af Navnet; på den plads, hvor
teksten siger יהוה, er den et ord, der skjuler Navnet. Her står det, der er
skrevet.

*Gud* er et godt dansk ord — **men det er ikke Navnet.**

Bøjning er i orden, så længe stammen forbliver hel: **Jahve, Jahves.** Det,
der ikke må ske, er, at stammen brydes — ikke *Jahvens*, ikke *Jahvs*.

## Almindeligt *gud* og *herre* er i orden

Hvor hebraisk taler om folkenes guder eller om en menneskelig herre, står der
her lille *gud*, *guder*, *herre*, *min herre*. Det er ikke at skjule Navnet;
det er oversættelse. Det hebraiske tegn afgør, ikke det danske ord i sig selv.

## Ord, der bliver på hebraisk

Ikke hvert ord er oversat. Nogle beholder deres hebraiske form, fordi intet
dansk ord bærer dem uden at miste noget: **ruach** · **chesed** · **tsedek** ·
**Tora** · **Shabbat** · **Mishkan** · **mincha** · **Sheol** · **Mashiach**,
og målene **omer**, **efa** og **shekel**. `רוח` er ét ord, og det betyder
ånd, vind og ånde; den, der vælger mellem dem, besvarer i hvert vers et
spørgsmål, som hebraisk lader stå åbent.

## Personers og steders navne

Navnene skrives efter hebraisk lyd, med én stavemåde: **Avraham**,
**Jitschak**, **Jaakov**, **Moshe**, **Aharon**, **Jisrael**, **Mitsrajim**,
**Jerushalajim**. Det er den største forskel, en dansk læser vil se, og den
venter — som alt andet her — på et dansk øre.

Pagtens kiste, `ארון`, er **arken** — aldrig *Aron*, som er Aharons kirkelige
navn.

## Kun Tanakh

Dette er den hebraiske Bibel alene — de 39 bøger. Intet ord fra Det Nye
Testamente rækker tilbage ind i teksten. Den hebraiske grund er OSHB / WLC.

## Hele reglen

Den disciplin, teksten er vokset frem efter, står skrevet — på dansk — i
Selahs hovedarkiv: `docs/methodology/translation-discipline/da.md`.

## Status

Denne tekst er **en første gennemgang**. Den er ikke det sidste ord; den er
et vidne. Læs den ved siden af hebraisk.

Hvordan teksten blev til — og hvad der gik galt undervejs — står i
`PROVENANCE.md`. De vers, hvor en hånd eller en afgørelse har rørt
gengivelsen, og de spørgsmål, der stadig står åbne, står i `NOTES.md`.

## Licens

Creative Commons Kreditering-DelPåSammeVilkår 4.0 International
(CC BY-SA 4.0). Se `LICENSE.md`.
