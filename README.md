# Development-of-Deep-Learning-Techniques-for-Image-Resolution-Enhancement

This thesis deals with basic methodologies for improving low-resolution images to high-resolution, with the use of convolutional neural networks. There is an attempt to optimize networks in a variety of ways to achieve the best possible result. 
Two popular convolutional neural networks were implemented with the first being the Super Resolution Convolutional Neural Network (SRCNN), which was subsequently used as a starting point for comparing models and the second being Residual Dense Network (RDN) in which an attempt is made to be improved. We  use Squeeze and Excitation Blocks (SE), Efficient Squeeze and Excitation Blocks (ECA) and the addition of a Channel Attention (CA) to enhance RDN. The data on which their training is based are 91-Images and DIV2K. Optimizations are mainly based on the increase of convolutional layers, modifications or even combinations of other networks with aim to deplete as many advantages as possible. 

For the comparison and general evaluation of the models the metrics used are the Peak Signal To Noise Ratio (PSNR) and the Structural Similarity Index Measure (SSIM). 



 ![image](https://github.com/PanagiotisPatsias/Development-of-Deep-Learning-Techniques-for-Image-Resolution-Enhancement-Pytorch-/assets/141324290/9bfdeeac-df66-4533-8bba-b0afd9b27625)


The area we enlarged and used for our comparisons is shown in red. It is a point that contains sufficient information and can give us a good picture of the effectiveness of deep learning techniques.


<p align="center">
  <b>Scale 2</b>
</p>

<table>
  <tr>
    <th>Low resolution</th>
    <th>Bicubic</th>
    <th>RDN CA</th>
    <th>Original</th>
  </tr>
  <tr>
    <td><img src="https://github.com/PanagiotisPatsias/Development-of-Deep-Learning-Techniques-for-Image-Resolution-Enhancement-Pytorch-/assets/141324290/de2dfe74-0345-4d59-ae63-f2ee617a0036" alt="Low resolution" width="230"></td>
    <td><img src="https://github.com/PanagiotisPatsias/Development-of-Deep-Learning-Techniques-for-Image-Resolution-Enhancement-Pytorch-/assets/141324290/99928758-5e8b-4dae-aafd-aa89e31d6516" alt="Bicubic" width="230"></td>
    <td><img src="https://github.com/PanagiotisPatsias/Development-of-Deep-Learning-Techniques-for-Image-Resolution-Enhancement-Pytorch-/assets/141324290/8f25a7f4-70ff-4f40-bbf4-55083648de78" alt="RDN CA" width="230"></td>
    <td><img src="https://github.com/PanagiotisPatsias/Development-of-Deep-Learning-Techniques-for-Image-Resolution-Enhancement-Pytorch-/assets/141324290/d3e27aec-86ef-4079-8afe-95f5b6e92cd2" alt="Original" width="230"></td>
  </tr>
</table>



<p align="center">
  <b>Scale 3</b>
</p>

<table>
  <tr>
    <th>Low resolution</th>
    <th>Bicubic</th>
    <th>RDN CA</th>
    <th>Original</th>
  </tr>
  <tr>
    <td><img src="https://github.com/PanagiotisPatsias/Development-of-Deep-Learning-Techniques-for-Image-Resolution-Enhancement-Pytorch-/assets/141324290/a0317b51-422a-4aee-809f-1e31334c2cfd" alt="Low resolution" width="230"></td>
    <td><img src="https://github.com/PanagiotisPatsias/Development-of-Deep-Learning-Techniques-for-Image-Resolution-Enhancement-Pytorch-/assets/141324290/506a7416-ded5-46f0-88ca-892dfb87e088" alt="Bicubic" width="230"></td>
    <td><img src="https://github.com/PanagiotisPatsias/Development-of-Deep-Learning-Techniques-for-Image-Resolution-Enhancement-Pytorch-/assets/141324290/30930a88-f1eb-4ad6-abcd-e6bc9551e26b" alt="RDN CA" width="230"></td>
    <td><img src="https://github.com/PanagiotisPatsias/Development-of-Deep-Learning-Techniques-for-Image-Resolution-Enhancement-Pytorch-/assets/141324290/270ae11f-019d-48c1-becb-8bb9012b3448" alt="Original" width="230"></td>
  </tr>
</table>



<p align="center">
  <b>Scale 4</b>
</p>


<table>
  <tr>
    <th>Low resolution</th>
    <th>Bicubic</th>
    <th>RDN CA</th>
    <th>Original</th>
  </tr>
  <tr>
    <td><img src="https://github.com/PanagiotisPatsias/Development-of-Deep-Learning-Techniques-for-Image-Resolution-Enhancement-Pytorch-/assets/141324290/4daf699e-504c-4e9a-b874-11f23c7aedde" alt="Low resolution" width="230"></td>
    <td><img src="https://github.com/PanagiotisPatsias/Development-of-Deep-Learning-Techniques-for-Image-Resolution-Enhancement-Pytorch-/assets/141324290/ffeef34b-a7a8-46e0-9081-7b32af7bcf5b" alt="Bicubic" width="230"></td>
    <td><img src="https://github.com/PanagiotisPatsias/Development-of-Deep-Learning-Techniques-for-Image-Resolution-Enhancement-Pytorch-/assets/141324290/3d12da27-b2d7-4aa3-990a-b0dafc60ac40" alt="RDN CA" width="230"></td>
    <td><img src="https://github.com/PanagiotisPatsias/Development-of-Deep-Learning-Techniques-for-Image-Resolution-Enhancement-Pytorch-/assets/141324290/3354a917-2696-4846-8013-7ebf49873b62" alt="Original" width="230"></td>
  </tr>
</table>


We see in all three scales that the image produced by RDN CA has better visual results than Bicubic and greatly improves the quality of the image.
