# BMP filter

You can apply picture filters such as edge detection on bmp files. The program creates the filteres copy of the image.

[You can read here about the Tideman method.](https://en.wikipedia.org/wiki/Ranked_pairs)

## Usage

- After compilation you can run the following command in terminal: 

```console
$ ./filter -<flag> <source.bmp> <filtered.bmp>
```

> 
- Max canidate number is 9
- For example: ./tideman Anna John Peter
- Ensure the number of voters with a positive whole number
- Type your preferences:
  - Rank 1: Candidate number 1
  - Rank 2: Candidate number 2
  ...

At the end you can see the name of the winner candidate(s).