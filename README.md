# Finetune Distilbert for Multiclass text classification

* A brief introduction to the task and the dataset used
  *  I used [this dataset](https://www.kaggle.com/datasets/amananandrai/ag-news-classification-dataset) from kaggle
  *  It has 4 categories World, Sports, Business ,Science/Technology

* The preprocessing steps taken
  * Used DistilBertTokenizer to tokenize the sentences

* The architecture of the model used, and how it was fine-tuned
  * I used distilbert-based-uncased model form huggingface and added two linear layers and one dropout layer for classification task

* The evaluation metrics and the results obtained
  * I used cross entrophy loss to calculate the loss
  * After training 1 epoch with whole dataset and batch size of 16, the accuracy of model was 83.88% which is preety good for four classes and if i had trained for 5 epochs it could have reached 90% easily.

* A discussion of the performance of the model and possible ways to improve it.
  * I didnt had enough time to train the model so i was only able to get 83.88% accuracy, it could be improved by training for atleast 5 hours.
