# Yolov5 model to mlmodel

This repo will help you to convert your yolov5 model trained weights v4.0, v5.0, v6.0 to mlmodel.

Note: This repos uses [coreml-tools](https://github.com/dbsystel/yolov5-coreml-tools) and [yolov5 version 4](https://github.com/ultralytics/yolov5/tree/v4.0) for conversion.

```
git clone https://github.com/Mu-Waleed/Yolov5_Coreml_Export.git
cd yolov5-coreml-tools
poetry install
```

```
poetry run coreml-export
```
Note: There is [conda.yaml](https://github.com/Mu-Waleed/Yolov5_Coreml_Export/blob/main/conda.yaml) for the exact module version I use in the environment. You can use same version if you face any issues.
