# Deep Sea eDNA Classification Pipeline

This project uses unsupervised learning to classify and annotate eDNA sequences from deep-sea samples.

## Folder Structure
- `data/train/`: FASTA files for training (from NCBI nt_euk).
- `data/test/`: FASTA files to classify.
- `outputs/`: saved models and classification results.
- `scripts/`: training and inference code.

## Usage
1. Place training files in `data/train/`.
2. Run `train_pipeline.py` to build models.
3. Place test FASTA files in `data/test/`.
4. Run `classify_pipeline.py` to classify and estimate abundance.
