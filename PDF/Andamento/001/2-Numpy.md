The topic is very broad: data
sets
can come from a wide range of sources and in a wide range of formats, including
collections of documents, collections of images, collections of sound clips, collections
of numerical measurements, or nearly anything else. Despite this apparent heteroge
neity,
many datasets can be represented fundamentally as arrays of numbers.

For example, images—particularly digital images—can be thought of as simply two
dimensional
arrays of numbers representing pixel brightness across the area. Sound
clips can be thought of as one-dimensional arrays of intensity versus time. Text can be
converted in various ways into numerical representations, such as binary digits repre
senting
the frequency of certain words or pairs of words. No matter what the data is,
the first step in making it analyzable will be to transform it into arrays of numbers.
(We will discuss some specific examples of this process in Chapter 40.)

This part of the book will cover NumPy in detail. NumPy (short for Numerical
Python) provides an efficient interface to store and operate on dense data buffers. In
some ways, NumPy arrays are like Python’s built-in
type, but NumPy arrays pro
list
vide
much more efficient storage and data operations as the arrays grow larger in size.