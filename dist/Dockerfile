FROM tensorflow/tensorflow

RUN mkdir /dist
COPY ./ /dist/
WORKDIR /dist
RUN pip3 install docopt hyperopt matplotlib pathlib numpy seaborn pandas fifty2-0.0.1-py3-none-any.whl

CMD ["fifty2", "whatis", "/dist/fifty_logo.png"]
