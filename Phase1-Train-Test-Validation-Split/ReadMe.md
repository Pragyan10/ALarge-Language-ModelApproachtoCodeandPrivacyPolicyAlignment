# Phase 1 - Dataset - Train | Validation | Test
The data for phase 1 is split into 3 sections: training, testing, and validation. 
For each of the section there are csv files that have the following list of columns with description to it:
1. Index -> Index order of the tokens.
2. AllParagraphID -> Paragraph id of the tokens. 
3. AllSentenceID -> Sentence id of the tokens. 
4. Token -> Token name.
5. Label -> Either a "Verb" or "O".
6. BIO-Label -> Label in BIO format ("B-Verb", "I-Verb", "O") for verbs following a longer sequence.
7. Label-DP-Association -> Verb Label added with its data practice and association. One out of 8 annotation. (FPCollect, FPTransfer, FPRetain, FPUse, TPUse, TPTransfer, TPRetain, TPCollect)
8. BIOLabelDPAssociation -> Label-DP-Association in BIO format verbs following a longer sequence. 