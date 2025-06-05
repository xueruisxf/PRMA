# Parameter Regularization and Dynamic Memory

Codes for our paper "[Improving Continual Relation Extraction via Parameter Regularization and Dynamic Memory]"

# Environment

- Python >= 3.8
- Torch >= 1.5.0

```
conda create -n prdm python=3.8
conda activate prdm
pip install -r requirements.txt
```

# Dataset

`FewRel` and `TACRED`:

- FewRel: `data/data_with_marker.json`
- TACRED: `data/data_with_marker_tacred.json`

# Run

```
bash bash/prdm.sh

```
