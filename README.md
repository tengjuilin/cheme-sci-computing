# Chemical Engineering Scientific Computing

[![License](https://img.shields.io/github/license/tengjuilin/cheme-sci-computing)](https://creativecommons.org/licenses/by/4.0/)
[![Website](https://img.shields.io/website?down_message=offline&up_message=online&url=https%3A%2F%2Fcheme-sci-computing.netlify.app%2F)](https://cheme-sci-computing.netlify.app/)

CHEME 375 covers Excel, Python, and ASPEN skills needed for chemical engineering applications. Applied scientific computing and numerical methods are covered. Taken in Sp21 with [Professor Jim Pfaendtner](https://www.cheme.washington.edu/facultyfinder/jim-pfaendtner).

## Optimization

|Topic|ChemE Applications|Python Skills|Jupyter <br/> Notebook|Online|
|-|-|-|:-:|:-:|
|Curve fitting|Fitting experimental data to functional forms (e.g. Clausius-Clapeyron equation)|`scipy.optimize.curve_fit()` <br/> `scipy.optimize.minimize()`|[ipynb](https://github.com/tengjuilin/cheme-sci-computing/blob/main/cheme-sci-computing/optimization/curve-fitting.ipynb)|[html](https://cheme-sci-computing.netlify.app/cheme-sci-computing/optimization/curve-fitting.html)|
|Solving linear systems|Balancing chemical equations|`scipy.linalg.inv()` <br/> `scipy.linalg.solve()`|[ipynb](https://github.com/tengjuilin/cheme-sci-computing/blob/main/cheme-sci-computing/optimization/solving-linear-systems.ipynb)|[html](https://cheme-sci-computing.netlify.app/cheme-sci-computing/optimization/solving-linear-systems.html)|
|Solving nonlinear systems|Solving binary vapor liquid equilibrium (VLE) problems|`scipy.optimize.fsolve()`|[ipynb](https://github.com/tengjuilin/cheme-sci-computing/blob/main/cheme-sci-computing/optimization/solving-nonlinear-systems.ipynb)|[html](https://cheme-sci-computing.netlify.app/cheme-sci-computing/optimization/solving-nonlinear-systems.html)|

## Programming

|Topic|ChemE Applications|Python Skills|Jupyter <br/> Notebook|Online|
|-|-|-|:-:|:-:|
|Control flow|VLE x/y diagram, Txy diagram|`scipy.optimize.fsolve()`|[ipynb](https://github.com/tengjuilin/cheme-sci-computing/blob/main/cheme-sci-computing/programming/control-flow.ipynb)|[html](https://cheme-sci-computing.netlify.app/cheme-sci-computing/programming/control-flow.html)|
|Comprehensive review|Determining Antoine's coefficients|`scipy.optimize.fsolve()`|[ipynb](https://github.com/tengjuilin/cheme-sci-computing/blob/main/cheme-sci-computing/programming/review-nonlinear-system-control-flow-curve-fitting.ipynb)|[html](https://cheme-sci-computing.netlify.app/cheme-sci-computing/programming/review-nonlinear-system-control-flow-curve-fitting.html)|
|Comprehensive review|Solving recycle streams|`scipy.linalg.solve()`|[ipynb](https://github.com/tengjuilin/cheme-sci-computing/blob/main/cheme-sci-computing/programming/review-linear-system-control-flow.ipynb)|[html](https://cheme-sci-computing.netlify.app/cheme-sci-computing/programming/review-linear-system-control-flow.html)|

## Differential Equations

|Topic|ChemE Applications|Python Skills|Jupyter <br/> Notebook|Online|
|-|-|-|:-:|:-:|
|Solving systems of ODEs|Chemical kinetics of one reaction and reaction networks|Euler's method <br/>`scipy.integrate.solve_ivp()`|[ipynb](https://github.com/tengjuilin/cheme-sci-computing/blob/main/cheme-sci-computing/differential-equations/solving-ode-systems.ipynb)|[html](https://cheme-sci-computing.netlify.app/cheme-sci-computing/differential-equations/solving-ode-systems.html)|
|Solving time-independent PDEs|Time-independent 2D heat transfer of thin metal slab|`scipy.linalg.solve()`|[ipynb](https://github.com/tengjuilin/cheme-sci-computing/blob/main/cheme-sci-computing/differential-equations/solving-time-independent-pdes.ipynb)|[html](https://cheme-sci-computing.netlify.app/cheme-sci-computing/differential-equations/solving-time-independent-pdes.html)|
|Solving time-dependent PDEs|Time-dependent 1D heat transfer of thin rod|Finite difference method|[ipynb](https://github.com/tengjuilin/cheme-sci-computing/blob/main/cheme-sci-computing/differential-equations/solving-time-dependent-pdes.ipynb)|[html](https://cheme-sci-computing.netlify.app/cheme-sci-computing/differential-equations/solving-time-dependent-pdes.html)|
