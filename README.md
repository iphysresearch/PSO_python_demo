# PSO_python_demo

Demo script (Python) of particle swarm optimization (PSO) partly translated from [SDMBIGDAT19](https://github.com/mohanty-sd/SDMBIGDAT19) (MATLAB).


- Slide: [https://slides.com/iphysresearch/pso](https://slides.com/iphysresearch/pso)
- Blog: [Particle Swarm Optimization From Scratch Using Python](https://slides.com/iphysresearch/pso)
- Video: [Bilibili](https://www.bilibili.com/video/BV1kv411h7sC/)



## Mock Data Challenge

- Given
  - Training data containing only noise: `TrainingData.mat`
  - Noise is Gaussian, stationary
  - Data to be analysed: `analysisData.mat`
  - **Signal**: Quadratic chirp
  - **Parameter search ranges**:
    - 40 < a1 < 100
    -  1 < a2 < 50
    - 11 < a3 < 15
- Detection and Estimation
  - Detection: Is there a signal in the analysis data?
  - Estimation: If so, estimate its parameters
  - Use PSO to obtain generalized likelihood ratio test (GLRT) and maximum likelihood estimate (MLE)
  - Recommended PSO parameters:
    - Best of 8 runs
    - Termination at 2000 iterations


## Pre-requirements

- Python 3.x
- Numpy
- Scipy
- tqdm


## How to use it

Just run [`demo.py`](https://github.com/iphysresearch/PSO_python_demo/blob/main/demo.py) script or [`demo.ipynb`](https://github.com/iphysresearch/PSO_python_demo/blob/main/demo.ipynb).

```python
$ python demo.py
```


## Reference

- 2021 Gravitational Wave Data Analysis School in China (Soumya D. Mohanty)
  - [https://github.com/mohanty-sd/GWSC](https://github.com/mohanty-sd/GWSC)
  - [https://github.com/BNUGW/GWSC21](https://github.com/BNUGW/GWSC21)

## Licence

- MIT
