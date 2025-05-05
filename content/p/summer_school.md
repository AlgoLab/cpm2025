<style type="text/css">
tbody { width:100%;background-color:#ddeeff;border-collapse:collapse; }
table { width:100%;background-color:#ddeeff;border-collapse:collapse; }
th { background-color:#ddeeff;color:white;width:50%;padding:1px;border:2px solid #ddeeff; }
td { padding:0px;border:2px solid #ddeeff; }
td { background-color: #c7fdb5; }
.table--bg--red { background-color: #ffcfdc;}
.table--bg--yellow { background-color: #ffffc2;}
.table--bg--green { background-color: #c7fdb5;}
.keynote { background-color: #ffffc2; padding: 5px; max-width: 10%; border: 1px solid #000; border-radius: 11px; display: inline}
.talk    { background-color: #c7fdb5; padding: 5px; max-width: 10%; border: 1px solid #000; border-radius: 11px; display: inline}
.break   { background-color: #ffcfdc; padding: 5px; max-width: 10%; border: 1px solid #000; border-radius: 11px; display: inline}
.cont    { display: inline; margin-top: -40px;}
</style>

# Summer school

The CPM summer school will take place **on June 12 and 13**, which are Thursday and
Friday of the week before the conference.

## Speakers

*  **Hideo Bannai**, Institute of Science Tokyo.
*  **Jonas Ellert**, École Normale Supérieure, Paris.
*  **Giulia Punzi**, University of Pisa.

## Location

University of Milan-Bicocca, U14-ABACUS building
[![map](/map-u14.jpg)](https://www.openstreetmap.org/way/23154089#map=19/45.523734/9.219992).
Click on the map for a larger map.

You can also check directions on [Google Maps](https://maps.app.goo.gl/Y4wqzV8Vgr8JnMB26) and [Apple Maps](https://maps.apple.com/?address=Viale%20Sarca%20336,%2020126%20Milano,%20Italia&auid=10195625695833040895&ll=45.523623,9.219530&lsp=9902&q=Dipartimento%20di%20Informatica,%20Sistemistica%20e%20Comunicazione%20DISCo&t=r).

## Registration

The registration deadline is June 10th. [Registration form](https://framaforms.org/cpm-2025-summer-school-1743617612).

The school is organized by Giulia Bernardini (giulia.bernardini[at]unimi.it), Gabriele Fici (gabriele.fici[at]unipa.it) and Raffaella Rizzi (raffaella.rizzi[at]unimib.it).

## Tentative schedule

### Thursday, June 12th

#### Lecture1  
#### 14:00-17:00 {.keynote}
##### Approximate Pattern Matching 101 (Jonas Ellert) {.cont}


Approximate pattern matching is a fundamental problem in string algorithmics. One version of this problem asks for approximate pattern occurrences with a small number of mismatches (i.e., with low Hamming distance). For example, the pattern "SummerIsCool" occurs in "CPM-SummerSchool-2025" with three mismatches. In this lecture, we consider offline algorithms that, given a pattern of length m, a text of length n, and an integer threshold k, find all approximate pattern occurrences with at most k mismatches. We delve into the most common techniques used by such algorithms, e.g.:

- using FFT to achieve O(n log m) time for constant alphabet,
- using an additional trick to achieve ~O(m*sqrt{m}) time for any alphabet,
- using Kangaroo jumps to achieve O(nk) time,
- selected techniques used by more advanced algorithms.

The lecture is aimed at students at all levels.

### Friday, June 13th

#### Lecture2  
#### 9:00-12:00 {.keynote}
##### Dictionary Compression and Repetitiveness Measures (Hideo Bannai) {.cont}


Dictionary compression is a family of compression methods that essentially represent data using “copy and paste” operations. This includes well-known methods such as LZ77, grammar-based compressors, and run-length compressed BWT. Compared to statistical methods, dictionary compressors can be more effective at modeling highly repetitive data, such as collections of genome sequences from the same species.
In this talk, I will give a (biased) survey of various dictionary compression methods and repetitiveness measures, discussing their relationships, recent developments, and open problems.

#### 12:00-14:00 {.break}
##### Lunch {.cont}  

####  

#### Lecture3  
#### 14:00-17:00 {.keynote}
##### Exploring the Relationships between Graph and String Problems (Giulia Punzi) {.cont}


Graphs are a fundamental tool in computer science, providing a versatile model of relationships between entities. The need to combine string problems with graph-theoretic approaches is becoming increasingly important, as information is often textual yet interconnected in a graph-representable way. Notable examples of this interplay include the World Wide Web graph, pangenome graphs, and automata theory.
In this lecture, we focus on a specific graph data structure used to encode string information: deBruijn graphs. Such graphs have been classically used in bioinformatics for genome sequence assembly applications. The nodes of a dBG represent the k-mers (length-k substrings) of an input text, while (directed) edges indicate overlaps of length k-1. We will introduce useful properties of deBruijn graphs, and show how some string-related problems can be approached through graph algorithms on dBGs.
