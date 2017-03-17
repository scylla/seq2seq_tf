# seqseq-autoencoder
This is a simple seqseq-autoencoder example of tensorflow
based on https://github.com/qixiang109/tensorflow-seq2seq-autoencoder


##1.Data
There is a chinese address dataset in data/address.txt, you can play with it, or you can use any whitespace-splited data with each token a single word and each line a single sequence.


##2.How to run
python train.py --data-path data/address.txt --model-path train

for more options: python train.py -h














