# Handwritten Text Recognition for Greek (grc)

This project is work in progress. 

The repository contains data used to train [Kraken](http://kraken.re/) text recognition and segmentation models for medieval Greek minuscule manuscripts within the framework of [eScriptorium](https://gitlab.com/scripta/escriptorium).

All images were collected using the IIIF-Services provided by the respective library (copyright may be claimed by the respective library, cf. the linked IIIF manifests in [MssList.md](MssList.md)). The original transcriptions were taken from [Vatican Library Greek Paleography](https://spotlight.vatlib.it/greek-paleography) (VAT in [MssList.md](MssList.md)) and from the [Patristic Text Archive](https://pta.bbaw.de). All transcriptions were manually corrected and amended by [Annette von Stockhausen](https://orcid.org/0000-0001-5382-6322).


Currently, the repository contains these folders and files:

- README.md: This file
- [MssList.md](MssList.md): List of manuscripts which have already been segmented and annotated
- [TranscriptionRules.md](TranscriptionRules.md): Rules applied in transcription
- [SegmentationRules.md](SegmentationRules.md): Rules for the segmentation
- data
	- will contain the images and transcriptions
- eScriptorium_helpers
	- [Greek manuscripts.json](/eScriptorium_helpers/Greek%20manuscripts.json): Virtual keyboard for special characters used in transcription
	- [ontology_escriptorium_grc.json](/eScriptorium_helpers/ontology_escriptorium_grc.json): Ontology for segmentation (adapting [SegmOnto](https://segmonto.github.io/))