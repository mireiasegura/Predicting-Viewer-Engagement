# Predicting-Viewer-Engagement
## Context
### Goal: predict viewer engagement in educational videos.

### Dataset: Educational video features from the VLE Dataset https://github.com/sahanbull/VLE-Dataset

#### Data fields in train.csv & test.csv:

-title_word_count - the number of words in the title of the video.

-document_entropy - a score indicating how varied the topics are covered in the video, based on the transcript. Videos with smaller entropy scores will tend to be more cohesive and more focused on a single topic.

-freshness - The number of days elapsed between 01/01/1970 and the lecture published date. Videos that are more recent will have higher freshness values.

-easiness - A text difficulty measure applied to the transcript. A lower score indicates more complex language used by the presenter.

-fraction_stopword_presence - A stopword is a very common word like 'the' or 'and'. This feature computes the fraction of all words that are stopwords in the video lecture transcript.

-speaker_speed - The average speaking rate in words per minute of the presenter in the video.

-silent_period_rate - The fraction of time in the lecture video that is silence (no speaking).

#### Data field in train.csv only:

-engagement - Target label for training. True if learners watched a substantial portion of the video (at least 30%), or False otherwise.
