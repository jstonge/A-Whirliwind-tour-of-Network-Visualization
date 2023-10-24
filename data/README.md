## Benson

link: [Sequences-Of-Sets#data](https://github.com/arbenson/Sequences-Of-Sets#data)

The datasets are in the data/ directory. The file data/dataset-seqs.txt is a list of sequences. Each line of the file has the following form:

size1,size2,…,sizeN;elmt1,elmt2,…,elmtM

    size1,size2,…,sizeN are the number of elements in the N sets in the sequence.
    elmt1,elmt2,…,elmtM are the M elements (given as integer identifiers) in the N sets in order. The first size1 elements are in the first set, the next size2 elements are in the second set, and so on. For each sequence, size1 + size2 + … + sizeN = M.

The files email-Enron-core-element-labels.txt, tags-math-sx-element-labels.txt, and tags-mathoverflow-element-labels.txt contain labels for the element.

bash-3.2$ head -5 email-Enron-core-element-labels.txt 
1 phillip.allen@enron.com
2 john.arnold@enron.com
3 harry.arora@enron.com
4 robert.badeer@enron.com
5 susan.bailey@enron.com

