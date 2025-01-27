# Grammar-error-correction model using t5 transformer
This project focuses on the development of an English grammar error correction system using the T5 model and implementing an Encoder-Decoder architecture from scratch. The goal is to create a robust and efficient tool that can automatically detect and correct grammatical errors in written English text.

Features
T5 Model Integration: The project leverages the Transformer-based T5 (Text-to-Text Transfer Transformer) model, known for its ability to handle a wide range of natural language processing tasks. The T5 model is fine-tuned specifically for English grammar error correction.
Encoder-Decoder Architecture: In addition to the pre-trained T5 model, This architecture enhances the model's understanding of contextual information and aids in generating accurate corrections for grammatical errors.

Model Training 
Fine-Tuning T5 Model: The T5 model is fine-tuned on a dataset containing annotated examples of grammatical errors. This ensures that the model is tailored to the specific task of English grammar correction.

Encoder-Decoder Training: The Encoder-Decoder architecture is trained on a parallel corpus of correct and incorrect sentences. The training process involves optimizing the model's parameters to minimize the difference between the predicted corrected sentence and the ground truth.

Dataset
https://www.kaggle.com/datasets/satishgunjal/grammar-correction/data
