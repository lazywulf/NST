# NST
###### Neural Style Transfer practice.

## Description
The code follows the original [NST paper](https://arxiv.org/pdf/1508.06576.pdf). Pytorch's tutorial on NSTs inspired parts of the implementation, so it may not follow some of the community's conventions.
The hyperparameters are listed in the "log" files.

## Notes on the output
1. The "failed" folder:
  - I accidentally calculated the style loss as content loss, resulting in the inputs being "stacked" on each other.
2. The "poke" folder:
  - A quite successful exp of The Starry Night and a sylveon drawing.

## Credit
- A Neural Algorithm of Artistic Style
  - https://arxiv.org/pdf/1508.06576.pdf
- The sylveon (content2)
  - artist: BloomingLynx
  - source: https://twitter.com/BloomingLynx/status/1478742701860343810
