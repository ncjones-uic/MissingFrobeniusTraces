Here is code verifying the computations and theorems of the manuscript

                              "Elliptic curves with missing Frobenius traces"

                                      By Nathan Jones and Kevin Vissuet

To reproduce those computations, please do the following:

First, copy the contents of the file Step1-LibraryOfFunctions.txt into a running MAGMA prompt. (Step 1 inputs the library of necessary functions.)

Next, copy the contents of Step2-MinimalMissingTraceGroups.txt into the same MAGMA prompt in batches, as indicated in the comments in the file. (Note: some of these computations are long and will require hours of machine time.) This script outputs the fifty-two subgroups of GL(2,Zhat) that are maximal among the genus zero  missing trace groups G satisfying det(G) = Zhat^*  (two of these groups fail to be admissible, in the sense that they do not contain an element that "looks like" the image of a complex conjugation; the other fifty groups are associated to the main theorem of the manuscript).
