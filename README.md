# sketchbook

This repository is a wrapper to hold all of the WCRS Arduino sketch repositories as submodules.  All maintained sketches can be obtained by cloning this single repository.

To clone this repository, including the submodules, use

```sh
git clone --recursive https://github.com/WCRSyyc/sketchbook.git
```

from the command line.

To later make sure that sketchbook, and all of the submodule sketches, are the lastest version from their individual repositories, change to the sketchbook folder, then

```sh
git pull
git submodule for each git checkout master
git submodule for each git pull
```

The issue tracker for this repository should be used for other sketches that should be added to this repository, or things that do not belong.  Comments and issues with individual sketches should go in the issue tracker for that submodule repository.  Issues that affect multiple sketches, or the interaction between them, can go here, **if** there is no other repository that already groups the related sketches together.

See the [github page](http://wcrsyyc.github.io/sketchbook/) for this repository.

[carbot](https://github.com/WCRSyyc/carbot), [asmac-display](https://github.com/WCRSyyc/asmac-display)
are repositories that also hold multiple sketches.  Related content belongs over there.
