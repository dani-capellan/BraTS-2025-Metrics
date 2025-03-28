# BraTS-2025-Metrics

This is an unofficial implementation of BraTS 2025 Metrics, which includes NSD as metric for evaluation. NSD is implemented according to [Lena Maier-Hein et al.](https://doi.org/10.1038/s41592-023-02151-z) with 2mm tolerance.

This is an extension of this code repository - [BraTS 2024 Performance Metrics](https://github.com/rachitsaluja/BraTS-2024-Metrics).

To use the code - 

```python
from metrics_{challenge} import *
results_df, _ = get_LesionWiseResults(pred_file, 
                      gt_file, 
                      challenge_name, 
                      output=None)
```

For the challenge name argument, the values are as follows - 

```
1. BraTS-GLI
2. BraTS-MEN-RT
3. BraTS-SSA
4. BraTS-PED
5. BraTS-MET
```