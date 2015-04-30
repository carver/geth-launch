This Custom Image
=============

Download Container:
> sudo docker pull carver/geth

Launch Container:
> sudo docker run -i -t carver/geth bash

In the Container:
> geth console

Built based on this [setup tutorial](https://docs.google.com/document/d/1fupguDpg-pB-EfBE7yqPEAtYQzXOo8iTd8rzIVggCs0/edit#heading=h.lp1k7b5k0stm)

Official Image
============

Download the prebuilt Docker image:
> docker pull ethereum/client-go

Open the command line to use with the [setup tutorial](https://docs.google.com/document/d/1fupguDpg-pB-EfBE7yqPEAtYQzXOo8iTd8rzIVggCs0/edit#heading=h.lp1k7b5k0stm):
> docker run -i --entrypoint=bash -t ethereum/client-go
