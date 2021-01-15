# FuseVis: Interpreting neural networks for image fusion using per-pixel saliency visualization
The project presents a visualization tool to interpret neural networks for image fusion. The tool, named as **FuseVis**, can be used by end-user to compute per-pixel saliency maps that examine the influence of the input image pixels on each pixel of the fused image. The tool can also be adapted to interpret any deep neural network that involves image processing. The work is based on the MDPI journal [paper](https://www.mdpi.com/2073-431X/9/4/98)

![GitHub Logo](/docs/Tool.png)


The tool performs the following key tasks:

*  Fast computation of per-pixel jacobian based saliency maps for the fused image with respect to input image pairs.
*  Visualize neural networks by considering the backpropagation heuristics using an interactive user interface that helps these networks to be more transparent in a real-time setup.

**Note**: Please cite the paper if you are using this code in your research.

## Prerequisites
* Python 2.7
* Pytorch 1.0 and above
* Tkinter
* numpy
* matplotlib
* skimage
* PIL
* imageio
* h5py

## Usage
Coming soon

## How to Cite
Kumar, N.; Gumhold, S. FuseVis: Interpreting Neural Networks for Image Fusion Using Per-Pixel Saliency Visualization. Computers 2020, 9, 98.

## Evaluated Neural Networks
![Logo1](/docs/Networks.png)
