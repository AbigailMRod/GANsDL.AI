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

## Conditional GAN
En este cuaderno, se creará una GAN condicional para generar imágenes de dígitos escritas a mano, condicionadas al dígito que se generará (el vector de clase). Esto permitirá elegir qué dígito se desea generar. Se utilizará la base de datos [MNIST](http://yann.lecun.com/exdb/mnist/).

## Controllable GAN
En este cuaderno, se implementará un método para controlar una GAN mediante gradientes de un clasificador. Al entrenar un clasificador para que reconozca una característica relevante, puede usarlo para cambiar las entradas del generador (vectores z) para que genere imágenes con más o menos de esa característica. Para este cuaderno, en lugar del conjunto de datos MNIST, utilizaremos [CelebA](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html). CelebA es un conjunto de datos de imágenes de celebridades comentadas. Dado que son de color (no en blanco y negro), las imágenes tienen tres canales para rojo, verde y azul (RGB).
