# Quantify-Battery-Losses-in-Transient-Driving-Cycles

In this paper, the parameters in battery RC link models are extracted from a physics-based model using
the pulse discharge method with different C-rates and fitting regions. A 2RC links model with parameters
obtained from 1C pulse discharge test has a better performance on the voltage and loss prediction.

There exist two fundamentally different kinds of battery cell models. One is based on the underlying
physics of the operation of the Li-ion cell and capturing the cell dynamics (physics based modelling).
Another method approximates the behaviour of the cell’s voltage in response to different input currents
(equivalent circuit modelling). Although not as accurate, the equivalent circuit modelling is preferred for
applications in battery management systems (BMS/BMU) due to its largely reduced computational complexity
compared to the physics based models, which contains much more degrees of freedom [1]. The method
to find the RC link parameters for Li-ion batteries from time domain data such as a pulse discharge test
is presented.
The contribution of this work is to quantify the battery RC link model accuracy with different parameter
extraction methods. A comparative study is presented where four C-rates are used in the pulse discharge
to characterize the cell. The model is validated under transient driving cycles and a physics based model
is used as the reference.
