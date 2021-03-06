# Interpolation with Python
This application uses polynomial interpolation with lagrange to take points and build a chart.

<img src = "http://support.ptc.com/help/mathcad/en/PTC_Mathcad_Help/images/example_polynomial_interpolation9.png" height="120" width="240">

The Lagrange interpolating polynomial is the polynomial P(x) of degree <=(n-1) that passes through the n points (x_1,y_1=f(x_1)), (x_2,y_2=f(x_2)), ..., (x_n,y_n=f(x_n)), and is given by

<img src = "https://mathworld.wolfram.com/images/equations/LagrangeInterpolatingPolynomial/NumberedEquation1.gif">

where

<img src = "https://mathworld.wolfram.com/images/equations/LagrangeInterpolatingPolynomial/NumberedEquation2.gif">

Written explicitly,

<img src = "https://mathworld.wolfram.com/images/equations/LagrangeInterpolatingPolynomial/Inline9.gif">

Reference: <a href="https://mathworld.wolfram.com/LagrangeInterpolatingPolynomial.html">Lagrange Interpolating Polynomialk</a>

### How to install
To run this project you will need to install `matplotlib`
Just run `py -m pip install -U pip &&  -m pip install -U matplotlib` to install pip and the `matplotlib`
Otherwise if you prefer to use `make` commands just use `make build`

### How to run
If you are using `Python 3.8.2` use the command `py main.py`
Otherwise if you prefer to use `make` commands just use `make run`
