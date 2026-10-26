MELD FILTERED CSV

I removed the rows of columns not containing the one of the four emotions that we are working with. 



  meld_train_filtered.csv  ->  train_splits
  meld_dev_filtered.csv    ->  dev_splits_complete
  meld_test_filtered.csv   ->  output_repeated_splits_test




  filename      name of the matching video clip (example: dia0_utt4.mp4)
  Emotion       emotion label for the clip
  Utterance     transcript of the line
  Speaker       character speaking
  Dialogue_ID   original MELD dialogue number
  Utterance_ID  original MELD utterance number

Essentially parse the csv matching the filename to one of the filenames in the download and then pull the corresponding emotion from the csv table. 


Download Link: https://affective-meld.github.io/
Extract train.tar, dev.tar, and test.tar. The train file is about 7.5 GB.



