# Computing Disjointness

This is a program written in python meant to help with computing the disjointness for a given code.  

## Running the Program

Given a set of stabilizer generators (written in binary symplectic form), run the following code:

    $ python main.py --stabilizer path/to/code.txt

If you only want to find the disjointness for a subset of stabilizers, you can write a file (in the same format) of 
representatives of logical pauli operators and run the following code:

    $ python main.py --stabilizer path/to/code.txt --paulis path/to/paulis.txt

If you want more detailed output, pass --verbose to the script.

For an example, a [[14, 3, 3]] stabilizer code is written in the proper format in the examples folder.

## More Information

This code is based off of work presented in this paper.