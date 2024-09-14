FROM python:3.9

WORKDDIR /nlp

COPY . /nlp

RUN conda install spacy==3.7.5
RUN pip install owlready2==0.46
RUN pip install pandas==2.2.2

CMD python test.py