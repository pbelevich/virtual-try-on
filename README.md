# Virtual Try-On
This is a non-commercial educational project that uses [FrankMocap](https://github.com/facebookresearch/frankmocap) for pose estimation, [MultiGarmentNetwork](https://github.com/bharat-b7/MultiGarmentNetwork) for garment re-targeting. FrankMocap's [PyTorch3D](https://pytorch3d.org/) renderer was modified to support textures from MultiGarmentNetwork's garments.

Original videos was taken from [shutterstock.com](https://www.shutterstock.com/)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pbelevich/virtual-try-on/blob/main/virtual_try_on.ipynb)

## Sample videos:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/z5ka8HIwTH0/0.jpg)](https://youtu.be/z5ka8HIwTH0)

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/iJE7L8jg3Qg/0.jpg)](https://youtu.be/iJE7L8jg3Qg)

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/72reazLNgso/0.jpg)](https://youtu.be/72reazLNgso)

## List of changes:

### FrankMocap

[Virtual Try-on Demo](https://github.com/pbelevich/frankmocap/compare/add_textures_to_p3d_renderer...pbelevich:virtual_try_on_demo)

[Add textures to FrankMocap's p3d_renderer](https://github.com/pbelevich/frankmocap/compare/master...pbelevich:add_textures_to_p3d_renderer)

### MultiGarmentNetwork

[Delete absolute paths](https://github.com/pbelevich/MultiGarmentNetwork/compare/python3...pbelevich:delete_absolute_paths)

[Update to Python 3](https://github.com/pbelevich/MultiGarmentNetwork/compare/master...pbelevich:python3)

## License

This non-commercial educational demo MIT licensed. See the license file [here](https://github.com/pbelevich/virtual-try-on/blob/main/LICENSE). It's based on [FrankMocap](https://github.com/facebookresearch/frankmocap) (Copyright (c) Facebook, Inc. and its affiliates) and [MultiGarmentNetwork](https://github.com/bharat-b7/MultiGarmentNetwork) (Copyright (c) 2019 Bharat Lal Bhatnagar, Max-Planck-Gesellschaft). It uses [PyTorch3d](https://github.com/facebookresearch/pytorch3d) (Copyright (c) Facebook, Inc. and its affiliates. All rights reserved.) renderer and [MPI-IS Mesh Processing Library](https://github.com/MPI-IS/mesh) to support [SMPL](https://smpl.is.tue.mpg.de/). Original low-resolution videos was taken from [shutterstock.com](https://www.shutterstock.com/)
