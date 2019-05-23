# 1410-Assignment-8

Arbitrarily Large Rational Numbers

The package "rational" contains BigRat.java, which is a modified version of the Rat example from the lecture of Wednesday, October 24.

As Rats are added and multiplied, their numerators and denominators can become too big to represent using long integers, which were used in the original Rat class.  You are to modify the Rat class so that it solves this problem and provides rational number objects with arbitrarily large numerators and denominators.

Here are the changes I have already made to the Rat class from lecture:

I have completed all of the implementations
I have renamed the class to BigRat
I have added one additional unimplemented constructor as detailed below
I have removed the toDouble method
You will need to change the representation, reimplement the existing methods and constructors, and implement the new constructor. (You will no longer need the gcd method and can get rid of it if you like.)  Java has a class called BigInteger (in the java.math package) that provides objects that represent arbitrarily long integers. You are to use BigInteger objects, instead of longs, to represent the numerator and denominator in your BigRat class.

Do not change the headers of any of the constructors or methods.  In particular, the two constructors that take longs as parameters should continue to take longs as parameters.

I strongly suggest that you begin by studying the specification of the BigInteger class, which you can find here (Links to an external site.)Links to an external site.. You will not need to use (or understand) most of the constructors or methods, but some will be very useful.  There are, for example, methods for performing the four basic arithmetic operations as well as gcd.  Do not call over a TA and ask him or her to explain how BigIntegers work. Try figuring it out for yourself by reading and experimenting before asking for help.  Being able to teach yourself about language and library features is a crucial skill that you should develop.

Don't forget to create a good collection of unit tests.  Add them to the BigRatTests class, which contain the unit tests from lecture plus one additional test.


Connect Four

The c4 package contains four classes:  C4Board, FourInARow, C4Display, and Connect4.  C4Board is a stub class whose implementation you are to complete.  FourInARow provides a static method that you will find useful when implementing C4Board.  You do not need to read or understand either C4Display or Connect4 unless you are curious.  When you correctly implement C4Board and run Connect4, you will have a Connect Four game that behaves identically to the model version that you can run by executing PS8Demo.jar.

If you are not already familiar with the rules of Connect Four, read the first paragraph of its Wikipedia article and play a few games with the demo program.  When you play the game, clicking in a column will place a piece into the first open spot in that column.  There is a circular indicator at the top of the window that shows you whose turn it is.

Carefully read the specifications in C4Board.  If you implement C4Board incorrectly, you will have a broken Connect Four game. If this happens, your inclination may be to blame me for making mistakes in one of the other classes.  Don't do this; fix your class instead! 

If you wish, you can ignore or modify my FourInARow class.

The key parts of implementing C4Board will be coming up with unit test cases and a representation plan.  Be sure to do both before beginning your implementation.  Put your unit tests in a C4Tests class.  Your grade will be based in part on your C4Board unit tests, and in part on your well-documented representation plan.
