NICSLU
============
About the name of the solver: NICS is the name of our lab in Tsinghua University ---- Nano-scale Integrated Circuits and Systems.<br><br>
Introduction: NICSLU is a high-performance, robust and thread-safe software package for solving large-scale sparse linear systems of equations (Ax = b) on multi-core shared-memory machines. It is written by C, and can be easily used in C/C++ programs. NICSLU is well suited for SPICE-based circuit simulation problems. There is no limitation of matrix dimension that NICSLU can handle with two exceptions: 1) your computer memory is not big enough; 2) you are using a 32-bit library.<br><br>
Performance of NICSLU: For a category of circuit matrices, sequential NICSLU has similar performance as KLU, while for the rest, sequential NICSLU is faster than KLU. Parallel NICSLU is slightly faster than PARDISO, and much faster than UMFPACK and SuperLU. Note that all these comparisons are only for circuit simulation problems. NICSLU is also proved to be high-performance in several state-of-the-art SPICE-based commercial simulators from several famous EDA companies. <br><br>
Authors' information: Please visit [Xiaoming Chen's personal page](http://people.ucas.edu.cn/~chenxm) or [Yu Wang's group page](https://nicsefc.ee.tsinghua.edu.cn/).
<br><br>

## License

#### For commercial purpose:

Please contact [Xiaoming Chen](mailto:chenxiaoming@ict.ac.cn) for commercial licenses. Please also note that the key techniques of NICSLU are protected by Chinese patents.<br>

#### For academic research:

You can use NICSLU for free. Once the license is expired, please contact [Xiaoming Chen](mailto:chenxiaoming@ict.ac.cn) to get a new license or download a new version. Please cite one or more of our papers when you publish your research if you have used NICSLU in your research.
