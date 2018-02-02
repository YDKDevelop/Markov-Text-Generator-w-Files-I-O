# Markov-Text-Generator-w-Files-I-O

# Sample Text
sample.txt can be any file

```
>>> word_dict = create_dictionary('sample.txt')
>>> word_dict
{'A': ['B', 'B', 'C.'], 'C': ['C', 'C.'],
 'B': ['A.', 'C.', 'A'], '$': ['A', 'A', 'B', 'C']}

>>> word_dict = create_dictionary('sample.txt')
>>> generate_text(word_dict, 20)
B C. C C C. C C C C C C C C C C C. C C C. A

>>> generate_text(word_dict, 20)
A B A. C C C. B A B C. A C. B A. C C C C C C.

```
