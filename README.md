# Parameter Regularization and Memory Augmentation

Codes for our paper "[Improving Continual Relation Extraction via Parameter Regularization and Memory Augmentation]"

# Environment

- Python >= 3.8
- Torch >= 1.5.0

```
conda create -n prma python=3.8
conda activate prma
pip install -r requirements.txt
```

# Dataset

`FewRel` and `TACRED`:

- FewRel: `data/data_with_marker.json`
- TACRED: `data/data_with_marker_tacred.json`

# Run

```
bash bash/prma.sh

```
