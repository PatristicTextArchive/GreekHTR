# Handwritten Text Recognition for Greek (grc)

This project is work in progress.

The repository contains data used to train [Kraken](http://kraken.re/) text recognition and segmentation models for medieval Greek minuscule manuscripts within the framework of [eScriptorium](https://gitlab.com/scripta/escriptorium).

Currently, the repository contains these folders and files:

- README.md: This file
- [MssList.md](MssList.md): List of manuscripts which have already been segmented and annotated
- [TranscriptionRules.md](TranscriptionRules.md): Rules applied in transcription
- [SegmentationRules.md](SegmentationRules.md): Rules for the segmentation
- eScriptorium_helpers
	- [Greek manuscripts.json](/eScriptorium_helpers/Greek%20manuscripts.json): Virtual keyboard for special characters used in transcription
	- [ontology_escriptorium_grc.json](/eScriptorium_helpers/ontology_escriptorium_grc.json): Ontology for segmentation (adapting [SegmOnto](https://segmonto.github.io/))