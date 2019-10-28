# 01_Continuous_approach
Examples of adjoint sensitivities calculated using the continuous approach for numerical groundwater flow models are presented.\
\
For most examples, both steady state and transient versions are presented, as the loading terms used in adjoint solutions are defined differently.

Launch interactive versions of the following Jupyter Notebooks using Binder:


### Sensitivities of modelled hydraulic head outputs to various model parameters: 

| Filename | Sensitivity to | Flow condition | Link |
| :------- | :------------- | :------------- | :--- |
| 01_dh_dK_SS.ipynb | Uniform hydraulic conductivity | Steady state | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F01_dh_dK_SS.ipynb) |
| 01_dh_dK_TR.ipynb | Uniform hydraulic conductivity | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F01_dh_dK_TR.ipynb) |
| 02_dh_dBC1h_SS.ipynb  | Dirichlet boundary head | Steady state | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F02_dh_dBC1h_SS.ipynb) |
| 02_dh_dBC1h_TR.ipynb  | Dirichlet boundary head | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F02_dh_dBC1h_TR.ipynb) |
| 03_dh_dBC2Q_SS.ipynb  | Neumann boundary flux | Steady state | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F03_dh_dBC2Q_SS.ipynb) |
| 03_dh_dBC2Q_TR.ipynb | Neumann boundary flux | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F03_dh_dBC2Q_TR.ipynb) |
| 04_dh_dQw_SS.ipynb | Source/sink term | Steady state | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F04_dh_dQw_SS.ipynb) |
| 04_dh_dQw_TR.ipynb | Source/sink term | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F04_dh_dQw_TR.ipynb) |
| 05_dh_dQr_SS.ipynb | Uniformly distributed flux | Steady state | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F05_dh_dQr_SS.ipynb) |
| 05_dh_dQr_TR.ipynb | Uniformly distributed flux | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F05_dh_dQr_TR.ipynb) |
| 06_dh_dBC3h_SS.ipynb | Robin boundary head | Steady state | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F06_dh_dBC3h_SS.ipynb) |
| 06_dh_dBC3h_TR.ipynb | Robin boundary head | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F06_dh_dBC3h_TR.ipynb) |
| 07_dh_dBC3c_SS.ipynb | Robin boundary conductance | Steady state | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F07_dh_dBC3c_SS.ipynb) |
| 07_dh_dBC3c_TR.ipynb | Robin boundary conductance | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F07_dh_dBC3c_TR.ipynb) |
| 08_dh_dSs_TR.ipynb | Robin boundary conductance | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F08_dh_dSs_TR.ipynb) |
| 09_dh_dICh_TR.ipynb | Uniform  initial condition head | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F09_dh_dICh_TR.ipynb) |

<br>

### Sensitivities of modelled velocity magnitude outputs to various model parameters: 

| Filename | Sensitivity to | Flow condition | Link |
| :------- | :------------- | :------------- | :--- |
| 11_dq_dK_SS.ipynb | Uniform hydraulic conductivity | Steady state | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F11_dq_dK_SS.ipynb) |
| 11_dq_dK_TR.ipynb | Uniform hydraulic conductivity | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F11_dq_dK_TR.ipynb) |
| 12_dq_dBC1h_SS.ipynb | Dirichlet boundary head | Steady state | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F12_dq_dBC1h_SS.ipynb) |
| 12_dq_dBC1h_TR.ipynb | Dirichlet boundary head | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F12_dq_dBC1h_TR.ipynb) |
| 13_dq_dBC2Q_SS.ipynb | Neumann boundary flux | Steady state | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F13_dq_dBC2Q_SS.ipynb) |
| 13_dq_dBC2Q_TR.ipynb | Neumann boundary flux | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F13_dq_dBC2Q_TR.ipynb) |
| 14_dq_dQw_SS.ipynb | Source/sink term | Steady state | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F14_dq_dQw_SS.ipynb) |
| 14_dq_dQw_TR.ipynb | Source/sink term | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F14_dq_dQw_TR.ipynb) |
| 15_dq_dQr_SS.ipynb | Uniformly distributed flux | Steady state | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F15_dq_dQr_SS.ipynb) |
| 15_dq_dQr_TR.ipynb | Uniformly distributed flux | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F15_dq_dQr_TR.ipynb) |
| 16_dq_dBC3h_SS.ipynb | Robin boundary head | Steady state | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F16_dq_dBC3h_SS.ipynb) |
| 16_dq_dBC3h_TR.ipynb | Robin boundary head | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F16_dq_dBC3h_TR.ipynb) |
| 17_dq_dBC3c_SS.ipynb | Robin boundary conductance | Steady state | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F17_dq_dBC3c_SS.ipynb) |
| 17_dq_dBC3c_TR.ipynb | Robin boundary conductance | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F17_dq_dBC3c_TR.ipynb) |
| 18_dq_dSs_TR.ipynb | Robin boundary conductance | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F18_dq_dSs_TR.ipynb) |
| 19_dq_dICh_TR.ipynb | Uniform  initial condition head | Transient | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F19_dq_dICh_TR.ipynb) |

<br>

### Sensitivities of modelled hydraulic head outputs to various model parameters: (analytical solution equivalents)

| Filename | Sensitivity to | Flow condition | Link |
| :------- | :------------- | :------------- | :--- |
| 21_dh_dK_Thiem.ipynb | Uniform hydraulic conductivity | Thiem | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F21_dh_dK_Thiem.ipynb) |
| 22_dh_dK_TR.ipynb | Uniform hydraulic conductivity | Theis | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christurnadge/03_First_order_adjoint_sensitivity/master/?filepath=01_Numerical_examples%2F01_Continuous_approach%2F22_dh_dK_Theis.ipynb) |
