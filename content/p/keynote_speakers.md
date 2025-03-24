<style type=text/css>
img {
	width: auto\9; /* ie8 */
	max-width: 200px;
	height: auto;
	vertical-align: bottom;
}
</style>

# Keynote speakers


###  [Inge Li Gørtz](https://www.imm.dtu.dk/~inge/) (Technical University of Denmark, Denmark)

![Inge Li Gørtz photo](https://www.imm.dtu.dk/~inge/inge-wb.jpeg)

#### Title: TBA

*Abstract:*

TBA


###  [Nicola Prezza](https://unive.it/data/persone/24170321) (Ca’ Foscari University of Venice, Italy)

![Nicola Prezza photo](https://www.unive.it/pag/fileadmin/user_upload/img/persone/24170321.jpg)

#### Title: Suffixient Arrays: a new Efficient Suffix Array Compression Technique

*Abstract:*

Compressed Suffix Arrays (CSA) have been introduced to reduce the space usage
of classic Suffix Arrays (SA), but at a big price: very poor cache locality at
query time. In practice, this translates to the fact that CSA are orders of
magnitude slower than Suffix Arrays. In this talk, I will propose a simple and
surprisingly efficient solution to this problem by showing that binary search
is still possible on a tiny sample of the Suffix Array: the Suffixient Array
(sA). The length of sA is never larger - and in some cases is asymptotically
smaller - than the number of runs in the Burrows-Wheeler Transform (BWT), a
powerful repetitiveness measure. Moreover, sA can be computed in linear time
and compressed working space and a sequence of simple binary searches on sA
allows one to solve pattern matching queries with near-optimal worst-case I/O
complexity. In practice, on repetitive DNA collections sA is simultaneously (i)
faster and orders of magnitudes smaller than SA and (ii) smaller and orders of
magnitude faster than the r-index (the state-of-the-art CSA for highly
repetitive data). These results should come at no surprise: the BWT is the I/O
bottleneck of CSA. To recover the time-efficiency of Suffix Arrays, it is suffi
(x)ient to completely remove the BWT and replace it with binary search on a
plain array (sA).

Based on joint work with Davide Cenzato, Lore Depuydt, Travis Gagie, Sung-Hwan
Kim, Giovanni Manzini, and Francisco Olivares.

###  [Kunihiko Sadakane](https://www.u-tokyo.ac.jp/focus/en/people/people100467.html) (The University of Tokyo, Japan)

![Kunihiko Sadakane photo](https://researchmap.jp/sada/avatar.JPG)


#### Title:  Compressed Suffix Arrays and Suffix Trees Revisited

*Abstract:*

Compressed suffix arrays and compressed suffix trees [Grossi, Vitter 2000, 2005]
are compressed data structures for string matching. These are linear
space (O(n log sigma) bits)
data structures where n is the length of the input string and sigma is
the alphabet size,
which are smaller than the traditional suffix arrays and suffix trees
using O(n log n) bit space.
Compressed suffix trees and arrays are extended to have more
functionalities [Sadakane 2003, 2007].
In this talk, we review these data structures and show further extensions.
