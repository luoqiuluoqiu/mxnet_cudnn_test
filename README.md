# mxnet_cudnn_test
* Use USE_CUDNN=1 to compile.
* Copy this example to `mxnet/tests/python/predict/` and replace the `mxnet_predict_example.py`.
* Run `mxnet_predict_example.py` to test the prediction of cuDNN and CPU.
* Given the result as follows:
```
./test/1.jpg
('Original Image Shape: ', (220, 400, 3))
(1L, 1000L)
('Top1: ', 'n09246464 cliff, drop, drop-off', 'Index: ', 972, 'Prob: ', 0.77454883)
(1L, 1000L)
('Top1: ', 'n09246464 cliff, drop, drop-off', 'Index: ', 972, 'Prob: ', 0.85431528)
```
* The probability between cuDNN and CPU is different.
