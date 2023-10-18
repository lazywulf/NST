# NST
###### Neural Style Transfer practice.

## Description
The code follows the original NST paper. Parts of the implementation were inspired by Pytorch's tutorial on NSTs, so it may not follow some of the community's conventions.
The hyperparameters are listed in the "log" files.

## Notes on the output
1. The "failed" folder:
  - I accidentally calculated the style loss as content loss which resulted in the inputs "stacked" on each other.
2. The "poke" folder:
  - A quite successful exp of The Starry Night and a sylveon drawing.

## Credit
- The sylveon (content2)
  - artist: BloomingLynx
  - source: https://twitter.com/BloomingLynx/status/1478742701860343810
