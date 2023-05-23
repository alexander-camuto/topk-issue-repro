# lstm-issue-repro

Reproduces the issue in https://github.com/zkonduit/ezkl/issues/233

To reproduce download the file at https://github.com/onnx/models/raw/main/vision/object_detection_segmentation/ssd/model/ssd-10.onnx to ./src/network.onnx

then run

```bash 


RUST_LOG=trace cargo run 

```
