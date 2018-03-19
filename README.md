code for the workshop（第10回脳科学若手の会 春合宿（2018/03/17 ~ 18））

'workshop.ipynb' includes :

    (0) load model
    (1) image recognition
    (2) estimating RF(receptive field) by reverse correlation
    (3) estimating RF by activation maximization
    (4) estimating prefered image by activation maximization (not only for first layer)
    (5) encoding and decoding experiment using Alexnet instead of a real brain
    (6) estimating tuning curve for orientation stimulus
    (7) decoding orientation using estimated tuning curve
    (8) image reconstruction from unit activities
    (9) deepdream

## preparation

*   put 'Alex.npz' in 'model' folder

*   put 'FMD.pickle', 'ImageNet.pickle', and 'Orientation.pickle' in 'data' folder for (5)

	*   These files were distributed in the workshop

*   put 'bvlc_googlenet.caffemodel' in 'model' folder for (9)

	*   This file is a pretrained model of googlenet
    
	*   'bvlc_googlenet.caffemodel' can be downloaded from https://github.com/BVLC/caffe/tree/master/models/bvlc_googlenet



(2), (3)

<img src="https://github.com/mrkmakr/workshop/blob/master/fig/RF_rc_am.png" alt="a" title="a">

(4)

<img src="https://github.com/mrkmakr/workshop/blob/master/fig/activation_maximization.png" alt="a" title="a">

(5)

<img src="https://github.com/mrkmakr/workshop/blob/master/fig/enc_dec_acc.png" alt="a" title="a">

(6)

<img src="https://github.com/mrkmakr/workshop/blob/master/fig/tuning_curve_and_weight.png" alt="a" title="a">

(7)

<img src="https://github.com/mrkmakr/workshop/blob/master/fig/orientation_decoding.png" alt="a" title="a">

(8)

<img src="https://github.com/mrkmakr/workshop/blob/master/fig/icnn.png" alt="a" title="a">

(9)

<img src="https://github.com/mrkmakr/workshop/blob/master/fig/dream.png" alt="a" title="a">
