# SRE Interview Question 2

Write a script that does the following:

1) Find the subdirectory of `data` that contains the most data.

2) In the directory from part 1, truncate the largest file(s)

3) In the directory from part 1, copy all files into a new directory under `data` named `output`. 

4) Rename all the files in `output` to start with `SRE_`.

3) Make all files in the `output` read-only for only the current user

## Discussion

Did you use a scripting language or built-in unix tools?

What are scenarios in a production environment that you would need to do similar tasks?