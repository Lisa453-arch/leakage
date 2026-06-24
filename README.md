# leakage

Water leakage dataset.

## Dataset layout

The dataset is stored without train/test split:

```text
dataset/
  water/
    images/   # 2392 images
    labels/   # 2392 YOLO label files
```

The original `train` and `val` folders have been merged into single `images` and `labels` directories.
