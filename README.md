# entropy
This project is related to PhD thesis in HSE University.

All text **corpora** and **program toolkits** can be found on *Realeases* https://github.com/Nastasian/entropy/releases/.

**The exclusive right** in the Computer Program was registred in *Rospatent* on 12 Decamber 2020 (Certificate № RU2020665906) https://fips.ru/publication-web/publications/document?type=doc&tab=PrEVM&id=AC1A7A31-4EDF-49EB-94BE-444830BFC41F.

Related articles:
1) http://asu.tgizd.ru/ru/arhiv/20171
2) https://www.researchsquare.com/article/rs-237508/v2


**MANUAL**

The program toolkit supports work with *Latin* and *Cyrillic* alphabets.
The algorithm consists of:
1) Preprocessing input text
2) Compiling token and n-gram **dictionaries** (for 10-,15-,20-,25-gramms)
3) Computing dictionary **coverage** and **entropy**.

**Note:** to work with Cyrillic text files, it must have the **UTF-8** or **Windows-1251** encoding.

**Input:** text file with a source corpus, a test sample for estimating of coverage (optional).

**Output:** text files "corpus_filt.txt", "test_filt.txt" (processed input files), "vocabulary.txt" (a dictionary with tokens), "10.txt", "15.txt", "20.txt", "25.txt" (dictionaries of n-grams), "information.txt" (a file with coverage and entropy computation results).
re

*How to work with the program: (macOS)*
1) Put the binary file "Toolkit_macOS", text file with your corpus and test sample file (optional) in the same folder (or be ready to specify the full path to your files).
2) At the command line, go to the folder where the binary file is located.
3) Specify that the file is executive (chmod 755 Toolkit_macOS). 
4) Start the program and specify a corpus file name and test file name (sudo ./Toolkit_macOS in.txt out.txt).

*4a) You can just start the program and specify files in the executive process (sudo ./Toolkit_macOS).* 
5) Choose the alphabet (1 - for Latin, 2 - for Cyrillic (UTF-8), 2 - for Cyrillic (Windows-1251)).
6) Enter a corpus file name.
7) Select if you have a test sample (1 - yes, 2 - no).
8) If you have a test sample enter test file name.
9) After the end of the program, all output files will be located in this folder.
