# 2025-syriac
Ground truth of 114 bifolio images of MS Jerusalem, Saint Mark's Monastery 36. This ground truth was produced by participants of the Vienna 2025 HTR Winter School, who used Transkribus to manually correct a preliminary automatic transcription that had been generated using a Kraken model (DOI [10.5281/zenodo.17406773](doi.org/10.5281/zenodo.17406773)).

## Description

- Jerusalem, Saint Mark's Monastery, MS 36
- Syriac, primarily Estrangelo but with Serto and Eastern features
- Codex approximately 12th - 14th century
- Scribe uncertain, perhaps the otherwise unknown Elias or Giwargis

### Origin of the data

{{FILL IN IMAGE SOURCE HERE}}

An online digitization of the manuscript may also be viewed in the virtual reading room of the Hill Museum & Manuscript Library at the shelfmark [SMMJ 00036](https://w3id.org/vhmml/readingRoom/view/126351).

### Segmentation and Transcription guidelines

The segmentation of the folios followed the [SegmOnto](https://segmonto.github.io/) vocabulary for annotation of regions: 

- `MainZone`: the main column of text.
- `MarginTextZone`: any marginal words or phrases, including catchwords. Also used for interlinear glosses.
- `NumberingZone`: any page or folio numbers.

The transcription guidelines included spaces, the Syriac letters, some diacritics, punctuation, and no vowel dots or markings.

- Allowed diacritics:
  - Syome
  - Dots over feminine suffix heh
  - Dots in pronouns: above for demonstrative, below for personal
  - Dots in verbs: to distinguish participles and perfects
  - Dots to distinguish homographs
- Excluded diacritics:
  - Vowel dots
  - Dots of hardening and softening (qushoyo and rukokho)
 
Punctuation marks were not normalized, but rather transcribed as they appear in the manuscript (. ܆ ܇ : ܀).

Transkribus's `unclear` tag was used when readings were uncertain or the text was damaged or unclear. There is additionally some use of the `sic` and `variant` tags in the corpus, but these were not applied consistently.

### Data organisation

- `CITATION.cff`
- `LICENSE.md`
- `README.md`
- `htr-united.yml`
- `SMMJ_00036`
  - `alto/`: the ground truth in ALTO XML format, exported from eScriptorium
  - `page/`: the ground truth in PAGE XML format, exported from Transkribus
  - `images/`: the corresponding image files

## How to cite

This dataset was created by: Ephrem Aboud Ishac, Christine Roughan, Julius Balski, Nima Jamali, Jeanette Kilicci, Chia-Wei Lin, Andrei Macar, Branko Malesevic, Stefan Maric, Daniele Reano, Rita Sawaya, and Jonathan Stutz.

If you use any item from this corpus as ground truth, cite the dataset using the following information:

```
{{ZENODO CITATION HERE}}
```

## Copyright and licence
This dataset was created as part of the Winter School of Handwritten Text Recognition of Medieval Manuscripts 2025, Vienna at the Österreichische Akademie der Wissenschaften, Institut für Mittelalterforschung, all transcriptions are licensed under the Creative Commons 4 licence. Images were provided by the {{IMAGE SOURCE HERE}} and are licensed under Creative Commons 4 licence.
