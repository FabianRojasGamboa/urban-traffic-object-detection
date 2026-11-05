# Publication and reproducibility notes

This package is an edited-for-publication copy of the 2024 academic project. The **original files are untouched**.

- The Colab notebook's execution outputs and transient metadata were removed to keep GitHub browsing lightweight. Three result images were preserved separately in `assets/`.
- The notebook's historical code is kept for provenance, including the Colab/Drive paths and the original training procedure. Some cells need path and dependency updates to work today.
- `data.yaml.example` is a portable illustration; the original model was trained with the original environment's dataset configuration. This example is **not** a claim that the exact run can be reproduced without the original data.
- Training and validation metrics are copied from the notebook, **not independently verified** or presented as held-out test metrics.
- `best.pt` and the large image dataset have deliberately been omitted. Check copyright, licensing, privacy and provenance before distributing either. Only load downloaded `.pt` weights from trusted sources, as PyTorch checkpoints can contain serialized Python objects.
- The source notebook's original title referenced 2D human pose estimation. The actual code and experiment perform urban traffic object detection; the repository title reflects that implemented task.
- The team members credited are Fabian Rojas, José Escobar, Armando Galaz and Matías Villanueva. Fabian reports particularly close technical collaboration with José; the exact division of work is not asserted beyond that.

To create the repository on GitHub, upload the **contents of this folder**, preserving subfolders. Do not upload this ZIP as a single file if you want GitHub to display the README and notebook.
