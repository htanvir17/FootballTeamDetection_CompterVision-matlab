# Football team detection
This repository contains the implementation of an algorithm that is able to detect different football teams following concepts of computer vision. The VC (computer vision) course was taken in 2021-Q2, spring season.

This project has two stages ([read the statement](statement.pdf))

The first goal is to detect if a Barça player appears in an image. In other words, only one class has to be recognized, which is Barca. This whole process has led us to make parameter decisions: which color model should be used, how many color components must be used, what is the size of the histogram, with which metrics to compare the histograms, how to make a global decision from the partial results, etc.
- [See the testing file](part1/example.pdf)

In the second part, the goal is to solve the recognition problem. It is the same as before with the same parameters but now it is necessary to find out which team appears on the scene.
- [See the testing file](part2/example.pdf)

## Members of this project
- Alejandro, Kenny
- Gorriz, Oriol
- Hossain, Tanvir
