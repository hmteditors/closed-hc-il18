# What's in this directory #

The file `alexandria.csv`  is a comma-delimited text file with on with four columns of data documenting each line of *liad* 18 in the Venetus A.  The four columns are:

1. URN for the *Iliad* line
2. Critical sign(s) on the line; value of `none` if there is no critical sign on the line.
3. Boolean value, `t` if scholia commenting on this line include one or more multiforms
4. Boolean value, `t` if scholia commenting on this line include one or more of the personal names Zenodotus, Aristophanes of Byzantium, Aristarchus

The file `Table of multiforms.md` presents the same results as `alexandria.csv` but in a tabulated format suitable for the chi-square test for independence.
