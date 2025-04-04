# argilla-audio-importer

A small utility to import audio data to Argilla using Rust.

It:

- Loads a dataset in parquet/arrow format
- Makes a spectrogram
- Encodes audio to base64 fields
- Adds data to your project in an Argilla instance
