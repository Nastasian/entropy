# entropy
This project is related to PhD thesis in HSE University.

All text **corpora** and **program toolkits** can be found on *Realeases* https://github.com/Nastasian/entropy/releases/.

**The exclusive right** in the Computer Program was registred in *Rospatent* on 12 Decamber 2020 (Certificate № RU2020665906) https://fips.ru/publication-web/publications/document?type=doc&tab=PrEVM&id=AC1A7A31-4EDF-49EB-94BE-444830BFC41F.

Related articles:
1) http://asu.tgizd.ru/ru/arhiv/20171
2) https://www.researchsquare.com/article/rs-237508/v1


**MANUAL**

The program toolkit supports work with *Latin* and *Cyrillic* alphabets.
The algorithm consists of:
1) Preprocessing input text
2) Compiling token and n-gram **dictionaries** (for 10-,15-,20-,25-gramms)
3) Computing dictinary **coverage** and **entropy**.

**Input:** text files "corpus.txt" (a source text corpus), "test.txt" (a test sample for estimating of coverage).
**Output:** text files "corpus_filt.txt", "test_filt.txt" (processed input files), "vocabulary.txt" (a dictionary with tokens), "10.txt", "15.txt", "20.txt", "25.txt" (dictionaries of n-grams), "information.txt" (a file with coverage and entropy computation results).
re

*How to work with the program:*
1) Put the binary file "Toolkit", text file with corpus named "corpus.txt" and test sample named "test.txt" (optional) in the same folder.
2) At the command line, go to the folder where the binary file is located. Start the program (./Toolkit). 
3) Choose the alphabet (0 - for Cyrillic, 1 - for Latin).
4) After the end of the program, all output files will be located in this folder.

