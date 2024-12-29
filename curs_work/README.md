# Convert COCO dataset to YOLO format

## Steps

1. **After load dataset move it to curs_work/datasets**

2. **Run COCO2YOLO.py for validation data:**

    ```bash
    python3 COCO2YOLO.py -j curs_work/datasets/fiftyone/coco-2017/validation/labels.json -o curs_work/datasets/fiftyone/coco-2017/validation
    ```

3. **Run COCO2YOLO.py for train data:**

    ```bash
    python3 COCO2YOLO.py -j curs_work/datasets/fiftyone/coco-2017/train/labels.json -o curs_work/datasets/fiftyone/coco-2017/train
    ```