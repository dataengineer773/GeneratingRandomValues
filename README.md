We want to generate pseudorandom value, The Solution is Use NumPy’s random, NumPy offers a wide variety of means to generate random numbers, many more than can be covered here. In our solution we generated floats; however, it is also common to generate integers
Alternatively, we can generate numbers by drawing them from a distribution (note this is not technically random), Finally, it can sometimes be useful to return the same random numbers multiple times to get predictable
repeatable results. We can do this by setting the “seed” (an integer) of the pseudorandom generato Random processes with the same seed will always produce the same output. We will use seeds throughout this book so that the code you see in the book and the code you run on your computer
produces the same results.
