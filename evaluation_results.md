# Model Evaluation Results

## Overall Performance

The multi-label IPC classification model was evaluated using subset accuracy, macro-averaged precision, recall, F1-score, micro F1-score, and Hamming loss.

| Evaluation Metric | Score |
|---|---:|
| Subset Accuracy | 27.62% |
| Macro Precision | 52.09% |
| Macro Recall | 80.17% |
| Macro F1-Score | 62.77% |
| Micro F1-Score | 61.86% |
| Hamming Loss | 16.33% |

## Per-Class F1-Score

| IPC Section | Offence | F1-Score |
|---|---|---:|
| 420 | Cheating | 0.86 |
| 376 | Rape | 0.81 |
| 498A | Cruelty by Husband/Relatives | 0.69 |
| 147 | Rioting | 0.64 |
| 302 | Murder | 0.62 |
| 201 | Causing Disappearance of Evidence | 0.46 |
| 506 | Criminal Intimidation | 0.33 |

## Performance Analysis

- The model achieved a macro recall of 80.17%, indicating its ability to identify a substantial proportion of relevant IPC labels.
- The macro F1-score of 62.77% reflects the balance between precision and recall across classes.
- Subset accuracy of 27.62% indicates that exact-match predictions across all labels remain challenging.
- IPC 420 achieved the highest class-wise F1-score (0.86), while IPC 506 recorded the lowest (0.33).

## Conclusion

The results demonstrate the potential of Sentence Transformer-based semantic representations combined with multi-label classification for legal case analysis. Differences in class-wise performance indicate opportunities for improving classification consistency and handling underrepresented or difficult categories.
