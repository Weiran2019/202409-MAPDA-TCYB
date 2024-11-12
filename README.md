# 202409-MAPDA-TCYB
Stealthy Measurement-Aided Pole-Dynamics Attacks with Nominal Models
# Introduction
When traditional pole-dynamics attacks (TPDAs) are implemented with nominal models, model mismatch between exact and nominal models often affects their stealthiness, or even makes the stealthiness lost. To solve this problem, our current paper presents a novel stealthy measurement-aided pole-dynamics attacks (MAPDAs) method with model mismatch. Firstly, the limitations of TPDAs using exact models are revealed. Secondly, to handle the limitations, the proposed MAPDAs method is designed by using an adaptive control strategy, which can keep the stealthiness. Moreover, it is easier to implement as only the measurements are needed in comparison with the existing methods requiring both measurements and control inputs. Thirdly, the performance of the proposed MAPDAs method is explored using convergence of multivariate measurements, and MAPDAs with model mismatch have the same stealthiness and similar destructiveness as TPDAs. Finally, experimental results from a networked inverted pendulum system confirm the feasibility and effectiveness of the proposed method.
# Running
Run the .m file in the every folders.
# Citation
If you find MAPDA scheme useful in your research, please consider citing:

``@ARTICLE{10688403,
  author={Du, Dajun and Zhang, Changda and Peng, Chen and Fei, Minrui and Zhou, Huiyu},
  journal={IEEE Transactions on Cybernetics}, 
  title={Stealthy Measurement-Aided Pole-Dynamics Attacks With Nominal Models}, 
  year={2024},
  volume={54},
  number={11},
  pages={6653-6666},
  keywords={Adaptation models;Analytical models;Loss measurement;Detectors;Synchronous machines;Sensors;MIMO communication;Adaptive control;convergence;model mismatch;pole-dynamics attacks (PDAs);stealthiness},
  doi={10.1109/TCYB.2024.3456084}}``
