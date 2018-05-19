# MXnet GPU install for R

Guide to installing GPU version of mxnet for R on AWS ubuntu base DLAMI

AWS guide for deep learning AMI (DLAMI)
https://aws.amazon.com/marketplace/pp/B077GCZ4GR
#default is p3 instance (~3.00/hr), I suggest building on g3 (<1.00/hr), create image+switch to p3 for heavy lifting

#their tutorial is great for Python users, but GPU-mxnet for R needs more indepth installation
https://docs.aws.amazon.com/dlami/latest/devguide/what-is-dlami.html

#MXnet installation instructions 
https://mxnet.incubator.apache.org/install/index.html
#choose linux, R and GPU
