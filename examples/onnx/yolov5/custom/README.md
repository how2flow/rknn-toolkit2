# rknn-toolkit2: custom

### Usage

- Let's assume that the working position is here.
- You must have all the packages associated with rknn-toolkit2 installed.
```
$ pwd
```
```
../rknn-toolkit2/examples/onnx/yolov5/custom
```

1. Copy your custom onnx file and test image to here.
```
$ cp {context}/{ONNX_MODEL} .
$ cp {context}/{TEST_IMG} ./test.jpg
```

2. Edit label list of your model in classes.txt
```
$ vi classes.txt # edit label list.
```

3. run custom.py
```
$ python custom.py --onnx {ONNX_MODEL} --rknn{RKNN_MODEL}
```

#### written by Steve Jeong (github.com/how2flow)

