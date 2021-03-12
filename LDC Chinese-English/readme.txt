
	LDC Chinese->English Translation Lexicon, Version 3
			April, 2002

https://www.cs.cmu.edu/afs/cs.cmu.edu/project/cmt-40/Nice/Transfer/Chinese/package/chinese_english_translation_lexicon/

1.  Background

   Back in 1999, out of urgent demand for a Chinese-English bilingual
wordlist in support of various TIDES projects, LDC quickly solicited both
in-house and Internet resources and compiled two versions of
Chinese-English wordlists, known as "ldc_ce_dict.1.0.gb" (henceforth V1)
and "ldc_ce_dict.2.0.txt" (henceforth V2), available for free to the
general public at http://www.ldc.upenn.edu/Projects/Chinese/.

   A large portion of V1 is based on the CEDICT project initiated by Paul
Denisowski (more information about this project and its development can be
found at http://www.mandarintools.com/cedict.html).  Its November 1998
revision (used in V1) has a relatively small and unbalanced coverage.  The
total number of entries is merely 23,510.  If one splits a regular Chinese
dictionary in half, one will find the CEDICT to have more coverage for the
first half than for the second half.

   The LDC's V1 had a slightly larger coverage with a total of 24,298
entries.  However, it has similar problems as the CEDICT version.
Research sites reported insufficient coverage, definitions not suitable
for machine translations, etc.  and showed great interest in having an
updated version.  This increasing demand lead to the birth of the present
release, "ldc_cedict.gb.v3" (henceforth V3).

   Note that V2, released shortly after V1, is not suitable for any
practical use.  Most of its entries were created by reversing various
English->Chinese wordlists and as a result many entries are not really
words.


2.  What's New in Version 3

   The total number of Chinese headwords in this release is 54,170.

   In terms of coverage, V3 is a superset of V1 and the LDC's Mandarin
pronunciation lexicon (v3/v4).  The pronunciation lexicon has a total of
44,404 entries, or 43,968 unique Chinese character strings (i.e.  with
pronunciation removed).  There are still 553 entries from the
pronunciation lexicon not found in V3.  We were unable to provide accurate
translations for these head words for various reasons: they may be very
technical; they don't make sense unless their source is re-examined; they
may have segmentation errors; or they may be rare words for which
appropriate translations could not be found due to limited time and
resources.

   V3 also left out less than 40 entries from V1.  Most of these are rare
single-character words whose translations cannot be verified for
correctness.

   As with V1, the basic format of each entry for the new release is still:

head_word_in_Chinese_characters <tab> /gloss 1/gloss 2/.../gloss n/

For example:

ººÓï	/Chinese language/Chinese/
Ó¢ÎÄ	/English language/English/

(If you are using a browser to read this file, it will need to be
Chinese-capable to read these characters.  You may need to change your
browser's Character Set to see Simplified Chinese [GB2312] characters.)

   Efforts have been made to assure:

(1) no duplicate glosses for any entry;
(2) no initial infinitival marker for verbs;
(3) no initial article for nouns;
(4) brackets (as explanations) are avoided if possible;
(5) more common translations (as intuitively predicted by annotators)
    appear earlier in the sequence of glosses; 
(6) avoidance of lengthy, elaborate translations if possible;
(7) no residual Chinese characters in the glosses;
(8) every gloss ending in -ation was checked to make sure a verb form is
    included wherever appropriate;
(9) complete spell-checking on all glosses based on modern American
    English.

   There are exceptions to (4)-(6).  For example, some grammatical words
may not have simple English "equivalents".  Often, they're given as many
glosses as one can think of.  But sometimes, the only way is to explain
how the word in question is used.  In such cases, brackets are used.
However, brackets usually appear later in the sequence unless no regular
gloss can be defined.

   The following table shows the distribution of alternate glosses per
Chinese headword; for example, 38,373 headwords have 1 gloss, 9,573 have
2 glosses, and so on (four Chinese words have 20 or more glosses):

#words #glosses
 38373  1
  9573  2
  3445  3
  1404  4
   664  5
   313  6
   173  7
    96  8
    54  9
    21  10
    17  11
     9  12
     7  13
     3  14
     6  15
     3  16
     2  17
     3  18
     1  20
     1  22
     1  23
     1  37


3.  Creation Procedures

   We extracted a list of headwords from the pronunciation lexicon that
did not have glosses in V1.  We first ran some machine translation software
on the list to get initial translations.  The list was divided into two
sub-lists.  One list has full English translations for each headword; these
translations were checked for accuracy and problems which were corrected by
hand.  The other list has partial or no translations at all.  We used
several hardcopy dictionaries as well as on-line resources to produce
appropriate translations by hand.

   The two lists with proper translations were then merged with V1 and
quality control was then performed on this master list.  See above,
"What's New in Version 3", for issues that were addressed during quality
control.


4.  Remaining Issues

   Not every entry from V1 has been checked.  Problems with entries from
V1 were corrected only if they were spotted while quality control was
being performed globally such as in the process of spell-checking.
Therefore, it's likely that some entries may still have lengthy
explanations, or a less common translation appears before a more common
translation for certain entries.  We hope to outline a set of more
consistent quality control guidelines for the next version.

5.  Credits

   Project Management and Chief Annotator: Shudong Huang
   Technical Support: David Graff
   Participating Annotators: Jennifer Chia, Fu-Dong Chiou, Jing Li, Jing
     (Jenny) Li, Tong Li, Jing Liu, Fang L. Norwood

