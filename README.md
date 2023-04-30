Download Link: https://assignmentchef.com/product/solved-cs260-machine-learning-algorithms-homework-3-solved
<br>
<table width="620">

 <tbody>

  <tr>

   <td width="524">  </td>

   <td width="96"></td>

  </tr>

 </tbody>

</table>

<strong>Instructions</strong>:

In this homework you will practice building a multi-class image classification pipeline to classify daily life images (CIFAR10), based on the modern neural networks. Please keep the batch size untouched. The goals of this homework are as follows:

<ul>

 <li>understand how to use Pytorch to build multi-class classifiers.</li>

 <li>understand the mechanism of convolution in image classification.</li>

 <li>learn the power of non-linearity in modern neural networks.</li>

 <li>implement and apply a fully-connected multi-class image classifier.</li>

 <li>implement and apply a Convolutional Neural Networks (CNN) classifier.</li>

</ul>

<strong>Problem Description.</strong>

In this homework, you are asked to implement fully-connected (MLP) and Convolutional Neural Networks (CNN) image classifier on CIFAR10 dataset. In this task, you only need to perform multi-class classification. Details of these models could be found in lecture 11 slides. We provide a skeleton code for data loading and iterations of training data. You are asked to implement the rest of training in Pytorch code. Detailed submission requirements are written in the final section.

<h1>Resources</h1>

You can follow the setup instructions at <a href="https://pytorch.org/get-started/locally/">https://pytorch.org/get-started/locally/</a><a href="https://pytorch.org/get-started/locally/">.</a>

A useful tutorial on learning building CNN at <a href="https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html">https://pytorch.org/tutorials/beginner/blitz/cifar10_ </a><a href="https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html">tutorial.html</a><a href="https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html">.</a>

Convolutional functions could be found here: <a href="https://pytorch.org/docs/stable/nn.html#convolution-functions">https://pytorch.org/docs/stable/nn.html#convolution-functions</a><a href="https://pytorch.org/docs/stable/nn.html#convolution-functions">.</a>

<h1>Data</h1>

We use CIFAR10 classification dataset. Pytorch/torchvision has provide a useful dataloader to automatically download and load the data into batches. We have written the data loader for you as follow. You can find it in the attached file.


