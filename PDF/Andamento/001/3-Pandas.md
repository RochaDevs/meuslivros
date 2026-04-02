Pandas is a newer package built on top of NumPy that provides an efficient
implementation of a DataFrame. DataFrames are essentially multidimensional arrays
with attached row and column labels, often with heterogeneous types and/or missing
data. As well as offering a convenient storage interface for labeled data, Pandas imple
ments
a number of powerful data operations familiar to users of both database frame
works
and spreadsheet programs.

As we’ve seen, NumPy’s
data structure provides essential features for the type
ndarray
of clean, well-organized data typically seen in numerical computing tasks. While it
serves this purpose very well, its limitations become clear when we need more flexi
bility
(e.g., attaching labels to data, working with missing data, etc.) and when
attempting operations that do not map well to element-wise broadcasting (e.g.,
groupings, pivots, etc.), each of which is an important piece of analyzing the less
structured data available in many forms in the world around us. Pandas, and in par
ticular
its
and
objects, builds on the NumPy array structure and
Series
DataFrame
provides efficient access to these sorts of “data munging” tasks that occupy much of a
data scientist’s time.

A Pandas
is a one-dimensional array of indexed data. It can be created from a
Series
list or array

The
combines a sequence of values with an explicit sequence of indices,
Series
which we can access with the
and
attributes. The
are simply a
values
index
values
familiar NumPy array: