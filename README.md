[![Build Status](https://travis-ci.org/sunix/flux-sequence-diagram.svg?branch=master)](https://travis-ci.org/sunix/flux-sequence-diagram)

flux-sequence-diagram
=====================

Sequence diagram that describes messages exchange between several Flux participant during a file system sync

## Requirements:
Install pic2plot command line:

    sudo apt-get install plotutils


## Generate the sequence diagram:

    pic2plot -Tsvg FluxFSSyncSD.pic >FluxFSSyncSD.svg
