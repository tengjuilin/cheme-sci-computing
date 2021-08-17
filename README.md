# Chemical Engineering Scientific Computing

[![License](https://img.shields.io/github/license/tengjuilin/cheme-sci-computing)](https://creativecommons.org/licenses/by/4.0/)
[![Visits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Ftengjuilin%2Fcheme-sci-computing&count_bg=%233D6AC8&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Visits+%28daily%2Ftotal%29&edge_flat=false)](https://hits.seeyoufarm.com)

CHEME 375 covers Excel, Python, and ASPEN skills needed for chemical engineering applications. Applied scientific computing and numerical methods are covered. Taken in Sp21 with [Professor Jim Pfaendtner](https://www.cheme.washington.edu/facultyfinder/jim-pfaendtner).

|Topic|ChemE Applications|Python Skills|Jupyter <br/> Notebook|Online|
|-|-|-|:-:|:-:|
|Curve fitting|Fitting experimental data to functional forms (e.g. Clausius-Clapeyron equation)|`scipy.optimize.curve_fit()` <br/> `scipy.optimize.minimize()`|[ipynb](curve-fitting.ipynb)|[html](https://tengjuilin.netlify.app/resources/cheme-sci-computing/curve-fitting.html)|
|Solving linear systems|Balancing chemical equations|`scipy.linalg.inv()` <br/> `scipy.linalg.solve()`|[ipynb](solving-linear-systems.ipynb)|[html](https://tengjuilin.netlify.app/resources/cheme-sci-computing/solving-linear-systems.html)|
|Solving nonlinear systems|Solving binary vapor liquid equilibrium (VLE) problems|`scipy.optimize.fsolve()`|[ipynb](solving-nonlinear-systems.ipynb)|[html](https://tengjuilin.netlify.app/resources/cheme-sci-computing/solving-nonlinear-systems.html)|
|Control flow|VLE x/y diagram, Txy diagram|`scipy.optimize.fsolve()`|[ipynb](control-flow.ipynb)|[html](https://tengjuilin.netlify.app/resources/cheme-sci-computing/control-flow.html)|
|Comprehensive review|Determining Antoine's coefficients|`scipy.optimize.fsolve()`|[ipynb](review-nonlinear-system-control-flow-curve-fitting.ipynb)|[html](https://tengjuilin.netlify.app/resources/cheme-sci-computing/review-nonlinear-system-control-flow-curve-fitting.html)|
|Comprehensive review|Solving recycle streams|`scipy.linalg.solve()`|[ipynb](review-linear-system-control-flow.ipynb)|[html](https://tengjuilin.netlify.app/resources/cheme-sci-computing/review-linear-system-control-flow.html)|
|Solving systems of ODEs|Chemical kinetics of one reaction and reaction networks|Euler's method <br/>`scipy.integrate.solve_ivp()`|[ipynb](solving-ode-systems.ipynb)|[html](https://tengjuilin.netlify.app/resources/cheme-sci-computing/solving-ode-systems.html)|
|Solving time-independent PDEs|Time-independent 2D heat transfer of thin metal slab|`scipy.linalg.solve()`|[ipynb](solving-time-independent-pdes.ipynb)|[html](https://tengjuilin.netlify.app/resources/cheme-sci-computing/solving-time-independent-pdes.html)|
|Solving time-dependent PDEs|Time-dependent 1D heat transfer of thin rod|Finite difference method|[ipynb](solving-time-dependent-pdes.ipynb)|[html](https://tengjuilin.netlify.app/resources/cheme-sci-computing/solving-time-dependent-pdes.html)|
