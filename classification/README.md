# Classification Problems
Classification problems of increasing complexity, built from scratch in PyTorch.

---

## Problems
| Notebook | Problem | Type | Key Concepts |
|----------|---------|------|--------------|
| 07 | Two Gaussian clusters | Binary | BCEWithLogitsLoss, sigmoid, decision boundary |
| 08 | Overlapping Gaussian clusters | Binary | Irreducible error, precision, recall, chaotic decision boundary |
| 09 | Multi-class Gaussian clusters | Multi-class | CrossEntropyLoss, softmax, argmax |
| 10 | Signal vs Noise | Binary | Temporal correlation, Nyquist, early stopping |
| 11 | Concentric rings *(upcoming)* | Binary | Nonlinear decision boundaries |

---

## Key concepts covered
- Sigmoid for binary output, CrossEntropyLoss for 3+ classes
- Irreducible error — overlapping classes set a hard accuracy ceiling
- Precision vs recall — in HEP, missing a rare signal is worse than a false alarm
- Confusion matrix — foundation of all classification metrics
- Overfitting looks like a chaotic decision boundary, not just rising val loss
- Temporal correlation as a physically meaningful classification feature
- Nyquist sampling theorem — frequency range must stay below fs/2
- Early stopping with patience counter
- Silent failure: missing `optimizer.step()` causes no error but no learning

---

*In progress — updating as problems are completed.*
