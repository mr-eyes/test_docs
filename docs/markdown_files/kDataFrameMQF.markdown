# kDataFrame class

kDataFrame has to subclasses, kDataFrameMQF and kDataFrameMAP.

- The maximum **kmer size** can be handled is `31`
- `kDataFrameMQF` is faster than `kDataFrameMAP` and has lower memory consumption.
- `kDataFrameMAP` is used when processing with **kmer size** < `15`
- kDataFrame set functions could be applied only on `kDataFrameMQF`
- Each of the two subclasses provides the same functions.
