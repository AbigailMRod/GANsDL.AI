# Generative Adversial Networks (GANs)
Ejercicios realizados dentro del Programa especializado: Generative Adversarial Networks (GANs), en Coursera.

Con ❤ Abigail Muñoz 

## FirstGAN
En este archivo se creó una red antagónica generativa (GAN).
Específicamente, se construyó y entrenó una GAN que puede generar imágenes escritas a mano de dígitos (0-9) utilizando PyTorch.
Las imágenes de entrenamiento que usará el discriminador provienen de un conjunto de datos llamado [MNIST](http://yann.lecun.com/exdb/mnist/). Contiene 60.000 imágenes de dígitos escritos a mano, del 0 al 9.

## DCGAN
En este archivo hay una GAN convolucional profunda.
Se construyó y entrenó una GAN que puede generar imágenes escritas a mano de dígitos (0-9) utilizando convolución profunda en PyTorch.
Las imágenes de entrenamiento que usará el discriminador provienen de un conjunto de datos llamado [MNIST](http://yann.lecun.com/exdb/mnist/). Contiene 60.000 imágenes de dígitos escritos a mano, del 0 al 9.

## WGAN
En este archivo se hizo una GAN de Wasserstein con penalización de gradiente.
Las WGAN resuelven algunos de los problemas de estabilidad con las GAN. Específicamente, se utilizará un tipo especial de función de pérdida conocida como W-loss, donde W significa Wasserstein, y penalizaciones de gradiente para evitar el colapso del modo. De igual manera se utiliza la base de datos [MNIST](http://yann.lecun.com/exdb/mnist/).
