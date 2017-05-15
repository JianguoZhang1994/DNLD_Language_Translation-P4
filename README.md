# DNLD_Language_Translation-P4
**Jianguo Zhang, May 11, 2017**

Training a sequence to sequence model on a dataset of English and French sentences that can translate new sentences from English to French

### Examples of results:

'He think she is beautiful.'

* Input
  * Word Ids:      [206, 172, 93, 98, 2]
  * English Words: ['he', 'think', 'she', 'is', '<UNK>']

* Prediction
  * Word Ids:      [83, 220, 182, 14, 159, 99, 140, 54, 251, 1]
  * French Words: ['nos', 'fruits', 'est', 'la', 'banane', ',', 'mais', 'mon', 'préféré.', '<EOS>']


'He saw a old yellow truck .'

* Input
  * Word Ids:      [206, 163, 179, 25, 36, 195, 38]
  * English Words: ['he', 'saw', 'a', 'old', 'yellow', 'truck', '.']

* Prediction
  * Word Ids:      [259, 165, 274, 179, 43, 196, 203, 1]
  * French Words: ['il', 'a', 'vu', 'un', 'vieux', 'camion', '.', '<EOS>']
