## Deep Graph Learning


<img src="https://pbs.twimg.com/media/DPJSagrX0AAYdSy.jpg">

This notebook contains the implementations of different deep learning algorithms applied on graphs.This includes implementations of SDNE and LINE, which fall under deep node embeddings. Both these embedding models are built in Tensorflow and rely on 2 order neighbors for generating the node representations. The intrinsic model is a simple linear Dense model with softmax activation to generate the embedding space.Post that there is an indepth implementation of Graph Neural Network architectures particularly suited for classifying node embedding representation from any networkx graph.This follows Thimas Kpif's vanilla spectral GCN, along with other variations of Spectral GNN including Laplacian GCN, Spline GCN and ChebNets. The implementations are also in Tensorflow /Keras.The following are the contents of the notebook:

## Deep Node Embeddings

### SDNE (Structural Deep Network Embeddings)

<img src="https://www.programmersought.com/images/979/223a8a8bc9b82f9255018d248c355c8b.png">

Resources

- [Paper](http://www.kdd.org/kdd2016/papers/files/rfp0191-wangAemb.pdf)
- [Github](https://github.com/suanrong/SDNE)

### LINE (Large Scale Information Network Embedding)

<img src="https://www.programmersought.com/images/996/f42357dccce22d2ee44665a2ece8e63c.png">

Resources

- [Paper](https://arxiv.org/abs/1503.03578v1)
- [Github](https://github.com/tangjianpku/LINE)


## Spectral Graph Neural 


<img src="https://image.slidesharecdn.com/smartbean-gcn-2019-03-07-naver-d2-sf-190311050200/95/graph-convolutional-neural-networks-22-638.jpg?cb=1552280822">


### Vanilla GNN

<img src="https://miro.medium.com/max/875/1*THVRB8-wHODA3yDUykasIg.png">

Resources

- [Paper](https://arxiv.org/abs/1609.02907)
- [Github](https://github.com/tkipf/gcn)

### Spline GCN

<img src="https://user-images.githubusercontent.com/6945922/38685459-42b2bcae-3e72-11e8-88cc-4b61e41dbd93.png">

Resources

- [Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Fey_SplineCNN_Fast_Geometric_CVPR_2018_paper.pdf)
- [Code](https://paperswithcode.com/paper/splinecnn-fast-geometric-deep-learning-with/review/)


### Laplacian GCN

<img src="https://atcold.github.io/pytorch-Deep-Learning/images/week13/13-2/Figure1.png">

- [Paper](https://arxiv.org/abs/1809.09839)

### ChebNets GCN

<img src="
https://camo.githubusercontent.com/8e2394416491aeb0064cefd8d9bbb5ac73e26006b5a56690a83938d8d0a59dc8/68747470733a2f2f692e6962622e636f2f516366684a524a2f53637265656e73686f742d323032302d30392d31372d61742d362d35302d32372d414d2e6a7067">

- [Paper](https://arxiv.org/abs/1911.05467)
- [Code](https://github.com/rusty1s/pytorch_geometric)


