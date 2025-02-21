# Emotion Recognition Using DANN and VGG19-Inspired CNN

This project provides an end-to-end pipeline for emotion recognition using visual (face) and auditory (speech) inputs. The implementation includes training, fine-tuning, testing, and real-time emotion recognition. The neural network is based on a modified VGG19 architecture with Domain-Adversarial Neural Networks (DANN) for domain adaptation.

---

## Features
- **Real-time emotion recognition** using webcam and microphone.
- **Model training pipeline** with fine-tuning on CK+ dataset.
- **Confusion matrix and classification report** for evaluation.
- **Domain adaptation** with DANN using gradient reversal.

---

## Files
 
### `train_final.ipynb`                                                                     
        It trains the model for 50 epochs on raf-db and fer2013 datasets                    
        the fine tune the model on ck+ combined with test folder in fer2013                 
### `test.ipynb`
        first part of the code youse your real laptop camera for inference
        second part it calculates confusion matrix on external dataset coming from  "https://www.kaggle.com/datasets/chiragsoni/ferdata/data"
    