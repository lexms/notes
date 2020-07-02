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
+ **Covariate  Shift**
    - Covariate shift is the change in distribution between training dataset and test dataset 

[🔙 Back](#navigation)

## D

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

[🔙 Back](#navigation)

## M

[🔙 Back](#navigation)

## N

+ **Neuroscience**
    - If your cells can turn into eyeballs or teeth, probably your cells can do backpropagation or something similar like backpropagation
    [[YouTube:
Preserve Knowledge]](https://www.youtube.com/watch?v=-eyhCTvrEtE)

[🔙 Back](#navigation)

## O

[🔙 Back](#navigation)

## P

[🔙 Back](#navigation)

## Q

[🔙 Back](#navigation)

## R
+ **Preview .md files in vscode**
    - Press Ctrl+Shift+V, [[src: Visual Studio]](https://code.visualstudio.com/docs/languages/markdown#:~:text=Markdown%20preview&text=To%20switch%20between%20views%2C%20press,with%20a%20very%20simple%20file.)


[🔙 Back](#navigation)

## S
+ **Sparse coding**
    - nan
+ **Skripsi**
    - print(netD.main[5].weight.size()) | torch.Size([256, 128, 4, 4]) artinya 256 feature maps out, 128 feature maps in, kernel 4x4
    - Every iteration convolution put different result for every feature maps

[🔙 Back](#navigation)

## T
+ **torch.detach**
    - detach(): remove a tensor from computation graph (excluded from further tracking of operations) [[src: B. Nikolic Software and Computing Blog]](http://www.bnikolic.co.uk/blog/pytorch-detach.html#:~:text=The%20detach()%20method%20constructs,visualised%20using%20the%20torchviz%20package.)
+ **torch.grad**
    - grad is a variable
    - torch.no_grad() to prevent memory overload [[src: PyTorch]](https://pytorch.org/tutorials/beginner/blitz/autograd_tutorial.html)

[🔙 Back](#navigation)

## U

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



