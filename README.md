# Illustration
Figure1: Gradient w.r.t. |w|

![alt text](https://github.com/ijairebutt/ijairebutt/blob/master/g1.png)


Figure2: Gradient w.r.t. |m|

![alt text](https://github.com/ijairebutt/ijairebutt/blob/master/g2.png)


Figure3:  Illustration of Consistent Gradient Directions w.r.t |w| and m

![alt text](https://github.com/ijairebutt/ijairebutt/blob/master/sign.png)


Figure4:  Sensitivity of m. Without learning rate compensation

![alt text](https://github.com/ijairebutt/ijairebutt/blob/master/v_ab_no_comp.png)


Figure5:  Sensitivity of m. With rescaling learning rate compensation

![alt text](https://github.com/ijairebutt/ijairebutt/blob/master/v_ab_comp_scale.png)

Comparison of gradients of m with and without learning rate compensation. Pure white values are 0 so associated gradients are zero. Without compensation, with larger |w|, m is more sensitive to change. After compensation, the larger the |w|, the smaller is the change in m.

Figure6: err_vs_cr. An illustration on the effectiveness of learning rate compensation for VGG-like model
![alt text](https://github.com/ijairebutt/ijairebutt/blob/master/cr_v_err.png)
