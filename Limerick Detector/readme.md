# Limerick Detector

- Developed a python application that implements natural language processing techniques to determine whether a section of text is a limerick.
- A limerick is considered to be a poem with the form AABBA, where the A lines rhyme with each other, the B lines rhyme with each other, and the A lines do not rhyme with the B lines.
- The script identifies limericks using CMU's dictionary of word pronunciations comprising of over 134,000 words.
- Two words are said to rhyme based on the similarity of syllable sounds using their vowel and consonant stresses obtained from the pronunciation dictionary.
- For words whose pronunciations are absent in the dictionary, an algorithm that best estimates the number of syllables in the word is implemented.
- Additional constraints in terms of the minimum number of syllables in each line and the maximum difference between the number of syllables in each line are used to accurately classify poems as limericks.
