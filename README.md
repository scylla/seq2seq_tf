# seqseq-autoencoder
This is a simple seqseq-autoencoder example of tensorflow
based on https://github.com/qixiang109/tensorflow-seq2seq-autoencoder

The nueral tranlation example in trensorflow can hardly be called a good example of seqence-to-sequence model. The functions it uses make tensorflow beginers like me puzzled. So I write a tie-seq2seq (which means the encoder and decoder use the same rnn network) short text auto encoder example, with simple structure and detailed comments.


##1.Data
There is a chinese address dataset in data/address.txt, you can play with it, or you can use any whitespace-splited data with each token a single word and each line a single sequence.


##2.How to run
python train.py --data-path data/address.txt --model-path train

for more options: python train.py -h














