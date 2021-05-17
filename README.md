# Image Reconstruction using AutoEncoders 
 

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#image-reconstruction">Reconstruction of CIFAR10 using AutoEncoder</a>
    </li>
    <li>
      <a href="#input-reconstruction-from-average-image">Reconstruction of input Images from the average of the input images (CIFAR10)</a>
    </li>
  </ol>
</details>

<!-- image-reconstruction -->
## Image Reconstruction

The repo contains a ipynb file for simple image reconstruction of cifar 10 using pytorch. Simple MSE loss is used with a single decoder. Skip connections are also used. Evaluation is done using SSIM, L1 and PSNR. 


<!-- image-reconstruction -->
## Input reconstruction from average image

The repo contains a ipynb file for input image reconstruction of cifar 10 from the average of the inputs using pytorch. A weighted loss of SSIM and L1 is used. I have used 2 decoders to reconstruct the two inputs seperately. Skip connections are also used. Evaluation is done using SSIM, L1 and PSNR. 




