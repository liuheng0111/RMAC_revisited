# RMAC_revisited

This code is used to illustrate the method presented in our paper: **RMAC Revisited: three strategies to improve object retrieval**

## Dataset
The [Oxford5k](http://www.robots.ox.ac.uk/~vgg/data/oxbuildings/) and [Paris6k](http://www.robots.ox.ac.uk/~vgg/data/parisbuildings/) object retrieval dataset.

## Pre-train deep Model
The [MatConvnet toolbox](http://www.vlfeat.org/matconvnet/) and the VGG-16 public model, which is provided by Tolias' ICLR2016 paper

    @article{tolias2015particular,
      title={Particular object retrieval with integral max-pooling of CNN activations},
      author={Tolias, Giorgos and Sicre, Ronan and J{\'e}gou, Herv{\'e}},
      journal={arXiv preprint arXiv:1511.05879},
      year={2015}
    }

## Evaluated Result
In matlab, run 'wm_test_spoc'
mAP, after re-ranking and QE = 0.818
