# mandelbrot-generator
generates an image of the madelbrot set

generate using ``target/release/mandelbrot_gen <img_name.png> <picture_size> <complex_num_1> <complex_num_2>``

example:

```
myPc:~/mandelbrot-generator/mandelbrot_gen$ time target/release/mandelbrot_gen mandelbrot_2.png 5000x3000 -1.20,0.34 -1,0.20

real    0m2.387s
user    0m7.217s
sys     0m0.010s
myPc:~/mandelbrot-generator/mandelbrot_gen$
```
![Alt text](/mandelbrot_gen/mandelbrot_2.png)
