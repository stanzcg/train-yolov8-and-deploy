# train yolov8 on cppe-5 dataset and deploy using onnxruntime and tensorRt

1.use dataprocess.ipynb to prepare datasets

2.run train.ipynb, get best.pt as well as export best.onnx

3.use onnx_deploy.ipynb to inference using onnxruntime

4.generate .wts

5.Run CMakeLists.txt with Cmake

6.Open project and run it
