
This is the README file for our submission in ICDM 2014: "Neural Conditional Energy Models for Multi-Label Classification".

We provide MATALB sources and all datasets we used in the experiments.



Credit:
=========================================================================================================================================================

The main body is built based on “DeepLearnToolBox” which is a MATLAB implementation of several interesting neural network models.

Learn more on their github page if interested: https://github.com/rasmusbergpalm/DeepLearnToolbox

The optimisation package in the directory is “minFunc” by Mark Schmidt.

Learn more about the software here if interested: http://www.di.ens.fr/~mschmidt/Software/minFunc.html

Purpose:
=========================================================================================================================================================

The current version of the code is purely for the reason to reproduce the results reported in the paper with NCEM.

There is no other guarantee. 

i.e. No comments on code. No documentation. No optimization for speed and readability. If I have time, I will try to improve it.

We will keep refining the code for later research usage.

Datasets:
=========================================================================================================================================================
There are 15 datasets stored in .mat format. All of them can be downloaded from the MULAN website: http://mulan.sourceforge.net/
{
	scene 
	emotions 
	yeast 
	medical 
	enron 
	rcv-subset1 
	rcv-subset2
	rcv-subset3 
	rcv-subset4 
	rcv-subset5 
	bibtex
	corel5k
	corel16k-sample1 
	corel16k-sample2
	corel16k-sample3
}


Usage:
=========================================================================================================================================================

There are 15 MATLAB scripts corresponding to 15 datasets.

To run the script and see the results for dataset "X", simply run "run_X". It will generate 10-fold train/test splits and run the model.

The results on ranking-loss, coverage, one-error, average-precision, micro-f1 will be stored in variables RL, COV, ONE, PRE, MI respectively.

The exact numbers may be slightly different from those reported in the paper due to random number generator.

Our MATLAB version is 2012b, I am not sure whether there will be any technical problem with older/newer versions.

