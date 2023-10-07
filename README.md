# dogvision
My attempt at the Zero To Mastery Udemy AI/ML Bootcamp "Dog Vision" image classification with TensorFlow project

The course uses Google Colab, but with some minor changes to directory names (filepaths) throughout I have this working on a local machine running Ubuntu 22.04.

The machine was a 14 year old (~2009) neglected home build with an Intel Core i7 940, a Noctua air cooler with a couple of fan blades missing (hence neglected!), 24GB DDR3, a GTX 260 graphics card, on an Asus P6T WS Pro mobo (LGA1366, aka Socket B, and PCIe v2). I replaced the air cooler with a new Cooler Master ML120L V2 RGB AIO liquid cooler, and upgraded the graphics card for a better CUDA/TensorFlow capable GPU (RTX 3060 TI). I also replaced several "small by todays standards" SAS and SCSI spinning drives with a single Crucial 1Tb SSD that I had laying around - so much less noise now!!  

Already, a deep learning neural network model which the course reports taking 2+ hours to train on 10,000 images on Colab (in 2020) can be trained on this machine in 15 seconds. Hard to believe, but that's my experience. I guess Colab is much more capable these days but I haven't tried, so can't confirm that. Regardless, my fairly small outlay (< £400) eliminates the would-be cost of additional Colab processing.

Model training on this machine is constrained by cpu. I have sourced (eBay) the fastest processor supported on this mobo (Xeon X5960) for £40 ($1666 new in 2011) to step up to 6 cores (12 threads) and 3.46 Ghz. I'm expecting ~15% faster which may make a difference for larger dataset processing. More later.
