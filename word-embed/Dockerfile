FROM floydhub/pytorch:0.3.0-gpu.cuda8cudnn6-py3.24

#RUN apt-get install curl
#RUN curl -o mecab.sh https://raw.githubusercontent.com/konlpy/konlpy/master/scripts/mecab.sh
#RUN bash mecab.sh

RUN apt-get install wget unzip
RUN wget https://github.com/facebookresearch/fastText/archive/v0.1.0.zip
RUN unzip v0.1.0.zip
RUN cd fastText-0.1.0
RUN make
RUN wget https://s3-us-west-1.amazonaws.com/fasttext-vectors/wiki.ko.zip
RUN unzip wiki.ko.zip
