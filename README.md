# Phi-4-mini — QLoRA / RAG Experiment Artifacts

Experiment repository containing parameter-efficient fine-tuning artifacts and code-repair evaluation outputs for **Phi-4-mini**.

## Published contents

- `partial_test_results_phi4-mini-qlora-rag-finetune-run1.csv`
- Trained adapter artifacts
- Multiple training checkpoints, including adapter weights, tokenizer files, trainer state, optimizer/scheduler state, and configuration metadata

## Repository role

This repository is primarily an **artifact archive**. It preserves training state and partial evaluation output rather than presenting one small deployable model package.

## Reproducibility / storage note

The checkpoint directories include large optimizer and tokenizer artifacts. For long-term publication, retain the selected adapter, exact configuration, final evaluation CSVs, and environment/reproduction instructions; intermediate optimizer state can be moved to external artifact storage if it is no longer needed for resuming training.

## Reporting note

Do not describe `partial_test_results...csv` as a completed full-test result unless row coverage is independently verified. Final performance numbers should be taken only from a confirmed complete result artifact produced under the documented protocol.

## Author

MD Alif Ziad Sarkar — CSE, American International University-Bangladesh (AIUB)
