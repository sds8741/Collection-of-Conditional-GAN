# Collection of Conditional-GAN

### Introduction

The conditional GAN (CGAN) is one of generative adversarial networks, which modify simple GANs structure
let the generator and discriminator are conditional during the training process so that the
generator can specify what label you want the generator produce.

However, the simple CGAN suffered from several issues such as Mode collapse and convergence
instability problems like simple GAN. When the generator produces limited varieties of
samples, this GAN failure is called model collapse. And convergence instability means GAN
convergence is often a fleeting, rather than stable state.

In this project, we want to implement some different training strategy or model structure in
CGAN to see if it can improve these problems. Both the training loss function curve and synthetic
images generate by different generator will be analyze and discussion.

### Contents:
+ **Project content details:** [Deep_Learning_Term_project.pdf](Deep_Learning_Term_project.pdf)
+ **Code:** [project.ipynb](project.ipynb)