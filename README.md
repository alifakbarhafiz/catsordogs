# catsordogs

Deep Learning Assignment Submission Repo

## Run

Google Colab, T4 GPU.

1. Upload `solution.ipynb`.
2. Runtime → Change runtime type → T4 GPU.
3. Runtime → Run all.
4. The last cell downloads `tugas05_outputs.zip`.

## Outputs


| File                      | What it is                                                                                             |
| ------------------------- | ------------------------------------------------------------------------------------------------------ |
| `outputs/metrics.csv`     | One row per run: trainable parameters, learning rate, epochs, time, validation accuracy, test macro F1 |
| `outputs/epoch_logs.csv`  | Train and validation loss and accuracy each epoch                                                      |
| `outputs/failures.csv`    | Test mistakes: true breed, prediction, confidence                                                      |
| `outputs/loss_curves.pdf` | Training and validation loss for B1, B2, and B3                                                        |
| `outputs/f1_bars.pdf`     | Test macro F1 for every run                                                                            |
| `outputs/failures.pdf`    | Eight test errors of the best checkpoint                                                               |
| `outputs/layer4_maps.png` | Mean `layer4` activation before and after fine-tuning                                                  |


