# Phase 2 - Dataset - Train | Validation | Test
The data for phase 2 is split into 3 sections: training, testing, and validation. 
For each of the section there are csv files that have the following list of columns with description to it:
1. Original Paragraph > Original Paragraph from the policy.
2. Document* -> Original Paragraph with <tgr> tag assigned to a verb.
3. Template -> A template to be filled based on the "Document*". <arg> is the placeholder that gets substituted with the infotype arguments
4. Output -> A filled Template where <arg> is replaced with the infotype argument associated with the <tgr> verb for the paragraph
5. And-Format -> Further processing Output so that multiple infotype argument are concatenated with "and"
6. Only-InfoType -> Only the infotype argument from the "And-Format"