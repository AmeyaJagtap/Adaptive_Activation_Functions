# Adaptive_Activation_Functions

We employ adaptive activation functions for regression in deep and physics-informed neural networks (PINNs) to approximate smooth and discontinuous functions as well as solutions of linear and nonlinear partial differential equations. In particular, we solve the nonlinear Klein-Gordon equation, which has smooth solutions, the nonlinear Burgers equation, which can admit high gradient solutions, and the Helmholtz equation. We introduce a scalable hyper-parameter in the activation function, which can be optimized to achieve best performance of the network as it changes dynamically the topology of the loss function involved in the optimization process. The adaptive activation function has better learning capabilities than the traditional one (fixed activation) as it improves greatly the convergence rate, especially at early training, as well as the solution accuracy. To better understand the learning process, we plot the neural network solution in the frequency domain to examine how the network captures successively different frequency bands present in the solution. We consider both forward problems, where the approximate solutions are obtained, as well as inverse problems, where parameters involved in the governing equation are identified. Our simulation results show that the proposed method is a very simple and effective approach to increase the efficiency, robustness and accuracy of the neural network approximation of nonlinear functions as well as solutions of partial differential equations, especially for forward problems. We theoretically prove that in the proposed method, gradient descent algorithms are not attracted to suboptimal critical points or local minima. Furthermore, the proposed adaptive activation functions are shown to accelerate the minimization process of the loss values in standard deep learning benchmarks using CIFAR-10, CIFAR-100, SVHN, MNIST, KMNIST, Fashion-MNIST, and Semeion datasets with and without data augmentation.

Code: PINN code for the Burgers equation (1 Dimension) 


If you make use of the code or the idea/algorithm in your work, please cite our papers

1. A.D. Jagtap, K.Kawaguchi, G.E.Karniadakis, Adaptive activation functions accelerate convergence in deep and physics-informed neural networks, Journal of Computational Physics, 404 (2020) 109136. (https://doi.org/10.1016/j.jcp.2019.109136)

       @article{jagtap2020adaptive,
       title={Adaptive activation functions accelerate convergence in deep and physics-informed neural networks},
       author={Jagtap, Ameya D and Kawaguchi, Kenji and Karniadakis, George Em},
       journal={Journal of Computational Physics},
       volume={404},
       pages={109136},
       year={2020},
       publisher={Elsevier}
       }

2. A.D.Jagtap, K.Kawaguchi, G.E.Karniadakis, Locally adaptive activation functions with slope recovery for deep and physics-informed neural networks, Proceedings of the Royal Society A: Mathematical, Physical and Engineering Sciences, 20200334, 2020. (http://dx.doi.org/10.1098/rspa.2020.0334).


       @article{jagtap2020locally,
       title={Locally adaptive activation functions with slope recovery for deep and physics-informed neural networks},
       author={Jagtap, Ameya D and Kawaguchi, Kenji and Em Karniadakis, George},
       journal={Proceedings of the Royal Society A},
       volume={476},
       number={2239},
       pages={20200334},
       year={2020},
       publisher={The Royal Society}
       }


3. A.D. Jagtap, Y. Shin, K. Kawaguchi, G.E. Karniadakis, Deep Kronecker neural networks: A general framework for neural networks with adaptive activation functions, Neurocomputing, 468, 165-180, 2022. (https://www.sciencedirect.com/science/article/pii/S0925231221015162)

       @article{jagtap2022deep,
       title={Deep Kronecker neural networks: A general framework for neural networks with adaptive activation functions},
       author={Jagtap, Ameya D and Shin, Yeonjong and Kawaguchi, Kenji and Karniadakis, George Em},
       journal={Neurocomputing},
       volume={468},
       pages={165--180},
       year={2022}
       }


Recommended software versions: TensorFlow 1.14, Python 3.6, Latex (for plotting figures)

In case of any queries, feel free to contact me at ameyadjagtap@gmail.com, ameya_jagtap@brown.edu 
