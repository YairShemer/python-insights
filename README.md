# Good practices when coding in python
* When run-time is a bottle neck, and you aren't using GPU, use multiprocessing.Pool.
* itertools.product is very usfull for easily generalizing nested loops.
* It is a good practice to have a seperate file for your input parameters (e.g. yaml). Save this file automatically every running.
* When using glob.glob, always sort the output: sorted(glob.glob()). You want to avoid randomness here.

