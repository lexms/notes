# Notes


## Navigation

+ [A](#a), [B](#b), [C](#c), [D](#d), [E](#e), [F](#f),
+ [G](#g), [H](#h), [I](#i), [J](#j), [K](#k), [L](#l),
+ [M](#m), [N](#n), [O](#o), [P](#p), [Q](#q), [R](#r),
+ [S](#s), [T](#t), [U](#u), [V](#v), [W](#w), [X](#x), [Y](#y), [Z](#z)

## Disclaimer
+ This is a note on how I interpret every tutorials, articles, and books that I read.
+ All sources will be cited, if not cited means it's based on personal experience 
+ There could be an information distortion, so I would be very grateful if you could tell me or let me know via [twitter](https://twitter.com/lexms_) or [linkedin](https://www.linkedin.com/in/lexms/)

## A

[🔙 Back](#navigation)

## B
+ **Boltzmann Machine**
+ **Backward Pass**
    - Call optimizer.zerograd() after each .step() prevent accumulating the gradient in .backward().

[🔙 Back](#navigation)

## C
+ **CNN: better understanding of cnn by visualize it**
    - 2D Visualize CNN [[src:ryerson.ca]](https://www.cs.ryerson.ca/~aharley/vis/conv/flat.html)
    - Visualizing convolutional features using PyTorch [[github: fg91]](https://github.com/fg91/visualizing-cnn-feature-maps)
    - pytorch_visualization [[github: pedrodiamel]](https://github.com/pedrodiamel/nettutorial/blob/master/pytorch/pytorch_visualization.ipynb)
    - pytorch-cnn-visualizations [[github: utkuozbulak]](https://github.com/utkuozbulak/pytorch-cnn-visualizations)
    - CNN Explainer [[github: poloclub]](https://github.com/poloclub/cnn-explainer)

+ **Covariate  Shift**
    - Covariate shift is the change in distribution between training dataset and test dataset 

[🔙 Back](#navigation)

## D
+ **DCGAN**
    - print(netD.main[5].weight.size()) | torch.Size([256, 128, 4, 4]) artinya 256 feature maps out, 128 feature maps in, kernel 4x4
    - Every iteration convolution put different result for every feature maps
    - if Loss D is near zero and Loss G still high means the generator generate garbage
    - Loss G 🔺 = fooling D with garbage, Loss D 🔻 = doesn't learn anything
    - Loss G 🔻 = generate good image, Loss D 🔻 = can distinguish fake n real



[🔙 Back](#navigation)

## E

[🔙 Back](#navigation)

## F
+ **Fractional Strided Convolution**
    - Transposed Convolution = Fractional Strided Convolution ≠ deconvolution [[src: ArXiv]](https://arxiv.org/abs/1603.07285) [[src: Implementing the Generator of DCGAN on FPGA]](https://www.theseus.fi/handle/10024/147406)
    - The number of *stride* in Convolution is equal to *half* of the *stride* in Transposed Convolution, 
    [[src: ArXiv]](https://arxiv.org/abs/1603.07285)
  
[🔙 Back](#navigation)

## G
+ **Training on GPU**
    - I found Tensorflow can harness more GPU power then PyTorch while training DCGAN using their tutorial's code

[🔙 Back](#navigation)

## H
+ **Hook PyTorch**
    - First create function for hook, then create model, then register hook

[🔙 Back](#navigation)

## I

[🔙 Back](#navigation)

## J

  
[🔙 Back](#navigation)

## K

[🔙 Back](#navigation)

## L
+ **Latent Space**
    - Latent Space is a compressed representation from certain dataset.

[🔙 Back](#navigation)

## M

[🔙 Back](#navigation)

## N

+ **Neuroscience**
    - If your cells can turn into eyeballs or teeth, probably your cells can do backpropagation or something similar like backpropagation
    [[YouTube:Preserve Knowledge]](https://www.youtube.com/watch?v=-eyhCTvrEtE)

[🔙 Back](#navigation)

## O

[🔙 Back](#navigation)

## P

+ **P Value**
    - p-value, the probability getting the current/original idea is TRUE or correct
    - The lower the P-value is the more significant your independent variable is going to be, the more impact on the dependent variable. <5% highly significant, >5% less significant

+ **Polynomial Linear Regression**
    - Rven though the relation between x and y is non linear you can use Polynomial Linear Regression


[🔙 Back](#navigation)

## Q

[🔙 Back](#navigation)

## R

+ **R**
    - name space seperated using dot

+ **Preview .md files in vscode**
    - Press Ctrl+Shift+V, [[src: Visual Studio]](https://code.visualstudio.com/docs/languages/markdown#:~:text=Markdown%20preview&text=To%20switch%20between%20views%2C%20press,with%20a%20very%20simple%20file.)


[🔙 Back](#navigation)

## S
+ **Data Security in ML**
    - Even with decentralized deep learning, GAN can generate protypical samples of targeted data. [[src: Arxiv]](https://arxiv.org/abs/1702.07464)
+ **Sparse coding**
    - nan


+ **Spyder**
    - An object cannot be viewed in spyder

[🔙 Back](#navigation)

## T
+ **torch.detach**
    - detach(): remove a tensor from computation graph (excluded from further tracking of operations) [[src: B. Nikolic Software and Computing Blog]](http://www.bnikolic.co.uk/blog/pytorch-detach.html#:~:text=The%20detach()%20method%20constructs,visualised%20using%20the%20torchviz%20package.)
+ **torch.grad**
    - grad is a variable
    - torch.no_grad() to prevent memory overload [[src: PyTorch]](https://pytorch.org/tutorials/beginner/blitz/autograd_tutorial.html)

[🔙 Back](#navigation)

## U
+ **Unbalanced Data**
    - Do oversampling or Undersamplng
[🔙 Back](#navigation)

## V

[🔙 Back](#navigation)

## W

[🔙 Back](#navigation)

## X

[🔙 Back](#navigation)

## Y

[🔙 Back](#navigation)

## Z

[🔙 Back](#navigation)

----



