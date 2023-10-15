These are the original treebank files, kept for the purposes of 
a) making any updates easier
b) preserving the original texts and text type split.

VALIDATION REPORT 2023-10

Sat Oct  7 19:01:55 CEST 2023
tools/check_files.pl UD_Maltese-MUDT
*** PASSED ***
./validate.sh --lang mt --max-err 0 UD_Maltese-MUDT/mt_mudt-ud-dev.conllu UD_Maltese-MUDT/mt_mudt-ud-test.conllu UD_Maltese-MUDT/mt_mudt-ud-train.conllu
[(in mt_mudt-ud-dev.conllu) Line 811 Sent 09_09J01:11 Node 21]: [L3 Morpho goeswith-upos] The UPOS tag of a 'goeswith'-connected word must be annotated only at the first part; the other parts must be tagged 'X'.
[(in mt_mudt-ud-dev.conllu) Line 7625 Sent 20_07J02:34 Node 24]: [L3 Morpho goeswith-upos] The UPOS tag of a 'goeswith'-connected word must be annotated only at the first part; the other parts must be tagged 'X'.
[(in mt_mudt-ud-test.conllu) Line 6813 Sent 42_04F09:23 Node 7]: [L3 Syntax too-many-subjects] Multiple subjects [5, 6] not subtyped as ':outer'. Outer subjects are allowed if a clause acts as the predicate of another clause.
[(in mt_mudt-ud-test.conllu) Line 7043 Sent 44_06F09:13 Node 10]: [L3 Syntax too-many-subjects] Multiple subjects [2, 9] not subtyped as ':outer'.
[(in mt_mudt-ud-train.conllu) Line 21169 Sent 55_02N11:41 Node 36]: [L3 Syntax too-many-subjects] Multiple subjects [22, 35] not subtyped as ':outer'.
[(in mt_mudt-ud-train.conllu) Line 21879 Sent 55_02N11:72 Node 14]: [L3 Syntax too-many-subjects] Multiple subjects [2, 13] not subtyped as ':outer'.
Morpho errors: 2
Syntax errors: 4
*** FAILED *** with 6 errors

TO DO:
Refine the analysis of multiple subjects.