FROM nsml/default_ml:tf-1.4.1

RUN wget https://s3-us-west-1.amazonaws.com/fasttext-vectors/word-vectors-v2/cc.ko.300.vec.gz
RUN gzip -d cc.ko.300.vec.gz

RUN pip3 install gensim

