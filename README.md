# DNLD_Language_Translation-P4
Training a sequence to sequence model on a dataset of English and French sentences that can translate new sentences from English to French

### Examples of results:

'He think she is beautiful.'

*Input
  Word Ids:      [2, 132, 174, 11, 172]
  English Words: ['<UNK>', 'think', 'she', 'is', 'beautiful']

*Prediction
  *Word Ids:      [333, 11, 249, 141, 142, 90, 167, 160, 249, 87, 48, 60, 351, 158, 1]
  *French Words: ['le', 'pamplemousse', 'est', 'notre', 'fruit', ',', 'mais', 'il', 'est', 'généralement', 'agréable', 'au', 'printemps', '.', '<EOS>']
