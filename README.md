# ONNX Backend Scoreboard<br/>Scoreboard for ONNX Backend Compatibility with Individual Ops<br/>[View HTML Scoreboard Here](https://ac2zoom.github.io/onnx-backend-scoreboard/)<br/>
Op                                        |  tensorflow                |  caffe2
------------------------------------------|----------------------------|--------------------------
ATen (Experimental)                       |  Failed!                   |  Failed!
Abs                                       |  Passed!                   |  Passed!
Acos                                      |  Passed!                   |  Passed!
Add                                       |  Passed!                   |  Passed!
Affine (Experimental)                     |  Failed!                   |  Failed!
And                                       |  Passed!                   |  Passed!
ArgMax                                    |  Passed!                   |  Passed!
ArgMin                                    |  Passed!                   |  Passed!
Asin                                      |  Passed!                   |  Passed!
Atan                                      |  Passed!                   |  Passed!
AveragePool                               |  Passed!                   |  Passed!
BatchNormalization                        |  Passed!                   |  Passed!
Cast                                      |  Passed!                   |  Failed!
Ceil                                      |  Passed!                   |  Passed!
Clip                                      |  Passed!                   |  Passed!
Concat                                    |  Passed!                   |  Passed!
Constant                                  |  Passed!                   |  Passed!
ConstantFill (Experimental)               |  Passed!                   |  Passed!
Conv                                      |  Passed!                   |  Passed!
ConvTranspose                             |  Passed!                   |  Passed!
Cos                                       |  Passed!                   |  Passed!
Crop (Experimental)                       |  Failed!                   |  Failed!
DepthToSpace                              |  Passed!                   |  Failed!
Div                                       |  Passed!                   |  Passed!
Dropout                                   |  Passed!                   |  Passed!
Elu                                       |  Passed!                   |  Passed!
Equal                                     |  Passed!                   |  Passed!
Exp                                       |  Passed!                   |  Passed!
Expand                                    |  Passed!                   |  Passed!
Flatten                                   |  Passed!                   |  Passed!
Floor                                     |  Passed!                   |  Passed!
GRU                                       |  Passed!                   |  Failed!
GRUUnit (Experimental)                    |  Failed!                   |  Failed!
Gather                                    |  Passed!                   |  Passed!
Gemm                                      |  Passed!                   |  Passed!
GivenTensorFill (Experimental)            |  Failed!                   |  Failed!
GlobalAveragePool                         |  Passed!                   |  Passed!
GlobalLpPool                              |  Failed!                   |  Failed!
GlobalMaxPool                             |  Passed!                   |  Passed!
Greater                                   |  Passed!                   |  Passed!
HardSigmoid                               |  Passed!                   |  Failed!
Hardmax                                   |  Passed!                   |  Failed!
Identity                                  |  Passed!                   |  Passed!
If                                        |  Failed!                   |  Failed!
ImageScaler (Experimental)                |  Failed!                   |  Failed!
InstanceNormalization                     |  Passed!                   |  Passed!
LRN                                       |  Passed!                   |  Passed!
LSTM                                      |  Passed!                   |  Passed!
LeakyRelu                                 |  Passed!                   |  Passed!
Less                                      |  Passed!                   |  Passed!
Log                                       |  Passed!                   |  Passed!
LogSoftmax                                |  Passed!                   |  Passed!
Loop                                      |  Failed!                   |  Failed!
LpNormalization                           |  Failed!                   |  Failed!
LpPool                                    |  Failed!                   |  Failed!
MatMul                                    |  Passed!                   |  Passed!
Max                                       |  Passed!                   |  Passed!
MaxPool                                   |  Passed!                   |  Passed!
MaxRoiPool                                |  Failed!                   |  Failed!
Mean                                      |  Passed!                   |  Passed!
MeanVarianceNormalization (Experimental)  |  Failed!                   |  Failed!
Min                                       |  Passed!                   |  Passed!
Mul                                       |  Passed!                   |  Passed!
Multinomial                               |  Failed!                   |  Failed!
Neg                                       |  Passed!                   |  Passed!
Not                                       |  Passed!                   |  Passed!
Or                                        |  Passed!                   |  Passed!
PRelu                                     |  Passed!                   |  Passed!
Pad                                       |  Passed!                   |  Passed!
ParametricSoftplus (Experimental)         |  Failed!                   |  Failed!
Pow                                       |  Passed!                   |  Passed!
RNN                                       |  Passed!                   |  Passed!
RandomNormal                              |  Failed!                   |  Failed!
RandomNormalLike                          |  Failed!                   |  Failed!
RandomUniform                             |  Failed!                   |  Failed!
RandomUniformLike                         |  Failed!                   |  Failed!
Reciprocal                                |  Passed!                   |  Passed!
ReduceL1                                  |  Passed!                   |  Failed!
ReduceL2                                  |  Passed!                   |  Failed!
ReduceLogSum                              |  Passed!                   |  Failed!
ReduceLogSumExp                           |  Passed!                   |  Failed!
ReduceMax                                 |  Passed!                   |  Passed!
ReduceMean                                |  Passed!                   |  Passed!
ReduceMin                                 |  Passed!                   |  Passed!
ReduceProd                                |  Passed!                   |  Failed!
ReduceSum                                 |  Passed!                   |  Passed!
ReduceSumSquare                           |  Passed!                   |  Failed!
Relu                                      |  Passed!                   |  Passed!
Reshape                                   |  Passed!                   |  Passed!
Scale (Experimental)                      |  Failed!                   |  Failed!
ScaledTanh (Experimental)                 |  Failed!                   |  Failed!
Scan                                      |  Failed!                   |  Failed!
Selu                                      |  Passed!                   |  Passed!
Shape                                     |  Passed!                   |  Passed!
Sigmoid                                   |  Passed!                   |  Passed!
Sin                                       |  Passed!                   |  Passed!
Size                                      |  Passed!                   |  Passed!
Slice                                     |  Passed!                   |  Passed!
Softmax                                   |  Passed!                   |  Passed!
Softplus                                  |  Passed!                   |  Passed!
Softsign                                  |  Passed!                   |  Passed!
SpaceToDepth                              |  Failed!                   |  Failed!
Split                                     |  Passed!                   |  Passed!
Sqrt                                      |  Passed!                   |  Passed!
Squeeze                                   |  Passed!                   |  Passed!
Sub                                       |  Passed!                   |  Passed!
Sum                                       |  Passed!                   |  Passed!
Tan                                       |  Passed!                   |  Passed!
Tanh                                      |  Passed!                   |  Passed!
ThresholdedRelu (Experimental)            |  Passed!                   |  Passed!
Tile                                      |  Passed!                   |  Failed!
TopK                                      |  Passed!                   |  Passed!
Transpose                                 |  Passed!                   |  Passed!
Unsqueeze                                 |  Passed!                   |  Passed!
Upsample                                  |  Passed!                   |  Passed!
Xor                                       |  Passed!                   |  Passed!
Summary                                   |  93/116 node tests passed  |  81/116 node tests passed

Model           |  tensorflow                    |  caffe2
----------------|--------------------------------|------------------------------
resnet50        |  9/9 nodes covered: Passed!    |  9/9 nodes covered: Passed!
bvlc_alexnet    |  8/8 nodes covered: Passed!    |  8/8 nodes covered: Passed!
inception_v2    |  12/12 nodes covered: Passed!  |  12/12 nodes covered: Passed!
squeezenet_old  |  7/7 nodes covered: Passed!    |  7/7 nodes covered: Passed!
inception_v1    |  10/10 nodes covered: Passed!  |  10/10 nodes covered: Passed!
vgg19           |  7/7 nodes covered: Passed!    |  7/7 nodes covered: Passed!
shufflenet      |  11/11 nodes covered: Passed!  |  11/11 nodes covered: Passed!
densenet121     |  10/10 nodes covered: Passed!  |  10/10 nodes covered: Passed!
Summary         |  8/8 model tests passed        |  8/8 model tests passed
    
# Adding Another Backend to the Scoreboard

To add another backend to the scoreboard, simply modify the Dockerfile [here](https://github.com/Ac2zoom/dockerfiles/blob/scoreboard/onnx-docker/onnx-docker-cpu/Dockerfile) to also install the relevant framework and backend.  Once this is done, add a call to pytest for the relevant test (subclass of [onnx.backend.test](https://github.com/onnx/onnx/tree/master/onnx/backend/test)) to [.travis.yml](https://github.com/Ac2zoom/onnx-backend-scoreboard/blob/master/.travis.yml).  Ensure that, before this test is run, `export BACKEND='<backend name>'` is added to the travis command in the Docker container before pytest is called.  This will ensure that the correct files are written.  Once this is done, the Travis CI will automatically generate the correct files and write to both the README and the CSV files rendered by the GitHub Page.
