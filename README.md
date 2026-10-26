# When Tuning Backfires

## Repository Structure

- `notebooks/general/` — Data preparation, preliminary tests, analysis, and verification.
- `notebooks/` — Experimental training, generation, scoring, and evaluation notebooks, organized into subfolders.
- `notebooks/execution_order.txt` — Execution order of all notebooks.
- `data/` — Dataset splits, exemplars, and OmniContext metadata.
- `results/scores/` — Automatic evaluation scores (JSONL).
- `results/embeddings/` — Saved image embeddings (NPZ).
- `results/human_eval/` — Human evaluation pairs, keys, and responses.

## External Resources

- OmniGen2 code: https://github.com/VectorSpaceLab/OmniGen2
- OmniGen2 model: https://huggingface.co/OmniGen2/OmniGen2
- X2I-subject-driven dataset: https://huggingface.co/datasets/yzwang/X2I-subject-driven
- OmniContext benchmark: https://huggingface.co/datasets/OmniGen2/OmniContext

## Environment

The notebooks were developed using Google Colab and Google Drive. Setup and package installation commands are included in the relevant notebooks.

Local file paths must be adjusted when running in another environment. Hugging Face and OpenAI API credentials are required for the relevant operations.

Original image datasets, generated images, and trained model checkpoints are not included.
