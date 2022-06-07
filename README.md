# chip8-benchmark
A simple benchmarking ROM for CHIP-8.

## How to use
#### If using an emulator:
- Download the `benchmark.ch8` file
- Load it in your emulator
- Start it
#### On [Octo](http://johnearnest.github.io/Octo/):
- Download the `benchmark.8o` file
- Open it with Octo
- Edit it if needed
- Start by clocking **"Run"**

## What to do with results
After about **4¼** seconds you should get a number printed on the screen. This is how many times the program has run through a loop. Here are some different emulator results that I've collected:
| ajor.co.uk/chip8 | Octo (1Kc./f.) | Octo (L. speed) | My emulator |
|------------------|----------------|-----------------|-------------|
| 206              | 20492          | 409823          | 2076        |

If the emulator beeps and does not print anything, there's an overflow and your result is higher than 10⁸. If this happens, just know: you have an absolute beast of a machine!

## Contributing
Feel free to contribute! But please do it via a pull request. Thanks!
