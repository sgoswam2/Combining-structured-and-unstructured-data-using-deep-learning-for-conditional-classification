# Combining structured and unstructured data using deep-learning for conditional classification modelling
This script uses deep learning model to extract features from unstructured data and combines with structured features and then applies ensemble models for conditional hierarchical classification.

<br>
For the unstructured text- each word is represented by an embedding layer, then we use phrase of words to get the embeddings, use Bidirectional LSTM to consider past and future sequences, finally we get the features for the entire document.
<br>
Then the features extracted from unstructured text by the above-mentioned DL method is concatenated directly with structured fields.
<br>
Followed by, we use feed-forward neural network to decode our conditional output.
<br>
Since its a consitional output classification, we take the feedback from the independent output section to the dependent output section.
