FROM nsml/default_ml:tf-1.4.1

RUN apt-get install wget unzip
RUN wget https://github.com/facebookresearch/fastText/archive/v0.1.0.zip
RUN unzip v0.1.0.zip
WORKDIR /fastText-0.1.0
RUN make

RUN wget https://s3-us-west-1.amazonaws.com/fasttext-vectors/word-vectors-v2/cc.ko.300.bin.gz
RUN gzip -d cc.ko.300.bin.gz

RUN pip3 install gensim

