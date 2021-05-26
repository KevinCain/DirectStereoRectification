# Direct Stereo Rectification
Analytic algorithm to compute best rectifying homographies that minimize perspective distortion and without using iterative methods.
An elaboration of the procedure originally introduced by Charles Loop and Zhengyou Zhang in _“Computing rectifying homographies for stereo vision”_ (1999), DOI: 10.1109/CVPR.1999.786928.

Full details in the **paper**:

>**Pasquale Lafiosca and Marta Ceccaroni, *"Rectifying homographies for stereo vision: direct method and implementation"*, Journal of Mathematical Imaging and Vision, 2021, URL https.//doi.org/**.

Cite as:
```
@article{DirectStereoRectification,
    author  = "Pasquale Lafiosca and Marta Ceccaroni",
    title   = "Rectifying homographies for stereo vision: direct method and implementation",
    year    = "2021",
    journal = "Journal of Mathematical Imaging and Vision",
    url = "https.//doi.org/"
}
```

## Dependencies
- Python 3 (tested with version 3.8.2)
- NumPy (tested with version 1.18.2)

OpenCV is required for the example only.

## Usage
See commented files [example.py](example.py) and [rectification.py](rectification.py).

## Disclamer
The code is provided "as is" wihout any warranty. For details see [LICENCE](LICENCE) file.
