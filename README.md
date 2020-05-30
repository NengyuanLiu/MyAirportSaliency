# AirportSaliency

a simple demo for paper 'Multi-Layer Abstraction Saliency for Airport Detection in SAR Images'

### Usage

1. Download `OpenCV 3.2.0` [here][id1], and copy the DLL file `opencv\build\x64\vc14\bin\opencv_world320.dll` to `utils\` folder.
2. Run `Demo.m` .

### Citation

```
@article{liu2019multi,
title={Multi-Layer Abstraction Saliency for Airport Detection in SAR Images},
author={Liu, Nengyuan and Cao, Zongjie and Cui, Zongyong and Pi, Yiming and Dang, Sihang},
journal={IEEE Transactions on Geoscience and Remote Sensing},
volume={57},
number={12},
pages={9820--9831},
year={2019},
publisher={IEEE}
}

@article{liu2018airport,
title={Airport detection in large-scale SAR images via line segment grouping and saliency analysis},
author={Liu, Nengyuan and Cui, Zongyong and Cao, Zongjie and Pi, Yiming and Dang, Sihang},
journal={IEEE Geoscience and Remote Sensing Letters},
volume={15},
number={3},
pages={434--438},
year={2018},
publisher={IEEE}
}
```



### Notice

- We only test this demo on MATLAB 2015b and 2016b.
- We use the LSD code in `LSD-OpenCV-MATLAB` which can be found [here][id2]. The original code and paper of LSD can be found [here][id3].

[id1]: https://opencv.org/opencv-3-2.html
[id2]: https://github.com/primetang/LSD-OpenCV-MATLAB
[id3]: http://www.ipol.im/pub/art/2012/gjmr-lsd/