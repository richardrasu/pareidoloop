pareidoloop
===========

1. generate random polygons
2. feed them into a face detector
3. mutate to increase recognition confidence

difficult stuff (the cv lib) by [liuliu]

idea via roger alsing's [evolution of mona lisa], and greg borenstein's [machine pareidolia]

[liuliu]: https://github.com/liuliu/ccv
[evolution of mona lisa]: http://rogeralsing.com/2008/12/07/genetic-programming-evolution-of-mona-lisa/
[machine pareidolia]: http://urbanhonking.com/ideasfordozens/2012/01/14/machine-pareidolia-hello-little-fella-meets-facetracker/

notes
=====
* try out a [demo]
* currently tested only in chrome (v 21)
* hangs firefox in some cases, on some OSes
* "autosave images" only works in chrome (uses a@download attribute)
* large output sizes result in corrupt images (data:// URLs too long?)
* probably a bunch of other bugs in there
* have patience - let it churn away for a few hours and see what you get
* annealing simulation from [russellmcc]

[demo]: http://iobound.com/pareidoloop/
[russellmcc]: https://github.com/russellmcc/pareidoloop
