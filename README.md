# RMAC_revisited

This code is used to illustrate the method presented in our paper: **RMAC Revisited: three strategies to improve object retrieval**, which is an extension of our conference paper (its public code is released in the [Fusion_RMAC](https://github.com/wangmaoCS/Fusion_RMAC)).

## Dataset
The [Oxford5k](http://www.robots.ox.ac.uk/~vgg/data/oxbuildings/) and [Paris6k](http://www.robots.ox.ac.uk/~vgg/data/parisbuildings/) object retrieval dataset.
The jpg image of the Oxford5k dataset should be placed in the path of './datasets/oxford5k/', and the same for the Paris6k dataset.

## Pre-train deep Model
The [MatConvnet toolbox](http://www.vlfeat.org/matconvnet/) is used to extract RMAC feature, and the VGG-16 public model is provided in Tolias' ICLR2016 paper

    @article{tolias2015particular,
      title={Particular object retrieval with integral max-pooling of CNN activations},
      author={Tolias, Giorgos and Sicre, Ronan and J{\'e}gou, Herv{\'e}},
      journal={arXiv preprint arXiv:1511.05879},
      year={2015}
    }

## Evaluated Result
In matlab, run 'wm_test_spoc'. 
Then the mAP after re-ranking and QE is 0.818 on the Oxford5k dataset
