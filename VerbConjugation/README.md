# Verb conjugation classes

Iranian Armenian has nearly the same set of verbal conjugation classes of Standard Eastern Armenian. In this folder, paradigms are provided in four types of files:

1. **[Arm](/VerbConjugation/TSV/Arm.tsv)**: paradigms in the Armenian script.
2. **[ArmStemmed](/VerbConjugation/TSV/ArmStemmed.tsv)**: paradigms in their transcribed form (IPA).
3. **[Trans](/VerbConjugation/TSV/Trans.tsv)**: stemmed paradigms in the Armenian script. 
4. **[TransStemmed](/VerbConjugation/TSV/TransStemmed.tsv)**: stemmed paradigms in their transcribed form (IPA). 

For stemmed paradigms, the paradigm cells are segmented into a stem and affixes. The files have both `xlsx` and `tsv` versions. 

The structure of a paradigm file looks like the following. This is taken from the [transcribed](/VerbConjugation/TSV/Trans.tsv) file.

| Class                  | E-Class      | E-Class      | A-Class       | ... | Suppletive                  |
|------------------------|--------------|--------------|---------------|-----|-----------------------------|
| Regularity             | Regular      | Regular      | Regular       | ... | Suppletive                  |
| Initial segment        | C            | V            | C             | ... | V                           |
| Example lemma          | jeɻkʰel      | uʁɒɻkel      | kɒɻtʰɒl       | ... | utel                        |
| Example gloss          | to sing      | to send      | to read       | ... | to eat                      |
| Example stems          | {X} = jeɻkʰ- | {X} = uʁɒɻk- | {X} = kɒɻtʰ-  | ... | {Xprs} = ut-, {Xpst} = keɻ- |
| infinitive             | jeɻkʰel      | uʁɒɻkel      | kɒɻtʰɒl       | ... | utel                        |
| ...                    | ...          | ...          | ...           | ... | ...                         |
| resultative participle | jeɻkʰɒt͡sʰ    | uʁɒɻkɒt͡sʰ    | kɒɻtʰɒt͡sʰɒt͡sʰ | ... | keɻɒt͡sʰ                     |
| subject participle     | jeɻkʰoʁ      | uʁɒɻkoʁ      | kɒɻtʰɒt͡sʰoʁ   | ... | utoʁ                        |
			
The different classes are organized on separate columns, starting from the second column. For example, the second column is for the E-Class.  The content of the paradigms is described on separate rows. The first 6 rows organize the classes in the following way:

1. **Class**: Name of the class. The terms are taken from the grammar.
1. **Regularity**: Type of class. Possible values are `Regular`, `Irregular`, `Defective`, or `Suppletive`.
1. **Initial segment**: The initial segment of all the lemmas of a class can either be a vowel `V` or a consonant `C`.
3. **Example lemma**: An example lemma that belongs to this classs, such as `jeɻkʰel`.
3. **Example gloss**: The gloss of the example lemma. 
4. **Example stem**: The stem of the example lemma. The stem is the part of the lemma without any suffixes, such as `jeɻkʰ-`. 

The stems are designed by symbols like `X` because some verbs have multiple stems, such as the verb `to eat`. 

The rest of the rows list the different paradigm cells, such as the `infinitive` or `subjective participle`. The meaning of each cell is discussed in the grammar. Some cells include multiple possible outputs, indicated by a slash ‘/’. Some cells are blank if the verb is defective for this cell. 

