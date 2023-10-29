# Neural Machine Translation for Human-Readable Dates

This repository contains my implementation of a neural machine translation (NMT) model for translating human-readable dates into machine-readable dates. The model is trained on a dataset of human-readable dates and corresponding machine-readable dates.

## Approach

The model is designed as an encoder-decoder architecture, with each encoder and decoder layer featuring a self-attention mechanism and a feed-forward neural network. The encoder learns to represent the input human-readable date as a sequence of hidden states, and the decoder then learns to generate the output machine-readable date by attending to these hidden states.

## Results

The model excels at accurately translating human-readable dates into machine-readable dates, even for complex date formats. Here are a few examples:

- Human-readable date: "25th of June, 2009"
  Machine-readable date: "2009-06-25"

- Human-readable date: "March 8th, 1975"
  Machine-readable date: "1975-03-08"

- Human-readable date: "August 12, 2023"
  Machine-readable date: "2023-08-12"

## Usage


You can leverage the model to translate human-readable dates in a variety of applications, including natural language processing, database management, and data science.

Feel free to clone the repository and experiment with translating your own human-readable dates into machine-readable formats.
