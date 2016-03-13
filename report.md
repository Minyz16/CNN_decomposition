# 毕设进展情况
## 2016/2/29
* 跑了caffe官网的一个例子 http://nbviewer.jupyter.org/github/BVLC/caffe/blob/master/examples/00-classification.ipynb
* 学习了ipython notebook基本用法（跑官网例子用）
* 尝试找kernal分解的code

## 2016/3/1
* 未找到基分解、迭代剪枝权重的代码实现
* 找到了kernal张量化的code: https://github.com/vadim-v-lebedev/cp-decomposition  官网：http://sites.skoltech.ru/compvision/projects/speeding-up-cnns/

## 2016/3/2
* 读了论文：SPEEDING-UP CONVOLUTIONAL NEURAL NETWORKS USING FINE-TUNED CP-DECOMPOSITION
* 读了该论文code（未全部完成），了解了code基本结构
* 配置该论文code所需环境

## 2016/3/3
* 了解了protobuf的使用方法，读了caffe代码中的caffe.proto,了解了用caffe写网络结构的基本流程
* 跑了官网的例子http://caffe.berkeleyvision.org/gathered/examples/mnist.html

## 2016/3/8
* 读完论文code，理解了code执行流程
* 尝试在服务器上跑通code，正在配置相关环境

## 2016/3/9
* 在实验室服务器上调通了code
* 粗略测量了一下mnist上加速后与加速前的数据，结果存放在 /cp-decomosition_results_on_CPU.txt
* 学习了finetuning的例子http://caffe.berkeleyvision.org/gathered/examples/finetune_flickr_style.html

## 2016/3/10
* 跑了官网例子：CIFAR-10 tutorial
* 读完了http://caffe.berkeleyvision.org/tutorial/，熟悉caffe，笔记写在 caffe tutorial笔记.txt
* 学习如何在caffe中添加自己的层







