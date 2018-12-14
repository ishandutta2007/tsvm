tsvm
====

The Goal of this project is to design and run data science
experiments to test various  transductive and semi-supervised
learning algorithms

The TSVM theory is described on my blog
http://charlesmartin14.wordpress.com/2014/07/06/machine-learning-with-missing-labels-transductive-svms/

The first objective is to test svmlin 
http://vikas.sindhwani.org/svmlin.html

against liblinear
http://www.csie.ntu.edu.tw/~cjlin/liblinear/

using the binary datasets provided for libsvm
http://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary.html

to determine how to tune svmlin well and what kind of data sets it performs well on

Later, we would like to look at Semi-Supervised learning algos such as

http://www.dii.unisi.it/~melacci/lapsvmp/

and the python scikit learn label propagation algo

http://scikit-learn.org/stable/modules/label_propagation.html



To get started

1.  download and install liblinear and svmlin


2.  download the a1a trainig and test data sets

http://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary/a1a

http://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary/a1a.t


3. edit svmlin, set the variables

SVMLIN_DIR = "~/packages/svmlin-v1.0"

LIBLINEAR_DIR = "~/packages/liblinear-1.94"

4. run
svmlin.rb a1a

5.  repeat for the a2a, a3a, ... data sets
and the w2a, w3a, ... data sets






### Support:

If you want the good work to continue please support us on

* [PAYPAL](https://www.paypal.me/ishandutta2007)
* [BITCOIN ADDRESS: 3LZazKXG18Hxa3LLNAeKYZNtLzCxpv1LyD](https://www.coinbase.com/join/5a8e4a045b02c403bc3a9c0c)
