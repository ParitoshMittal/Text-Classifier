# Text-Classifier
Notebook Summery
1. Use Tensorflow 2.x
2. Import Library
3. Dataset
  https://storage.googleapis.com/learning-datasets/sarcasm.json

  This dataset is News Headlines Dataset By Rishabh Misra from Keggle.
  
  Dataset have three Key elements:
  
  1. article_link
  2. headline
  3. is_sarcastic
  In case we only needs headline and is_sarcastic. headline as our text and is_sarcastic as label.
4. Load Data
5. Data Processing
6. Design Model
   _________________________________________________________________
   Layer (type)                Output Shape              Param   
   =================================================================
   embedding_3 (Embedding)     (None, 100, 16)           160000    
   
   global_average_pooling1d_3  (None, 16)                0         
   (GlobalAveragePooling1D)                                       

   dense_6 (Dense)             (None, 24)                408
   
   dense_7 (Dense)             (None, 1)                 25
   =================================================================
   Total params: 160433 (626.69 KB)
   Trainable params: 160433 (626.69 KB)
   Non-trainable params: 0 (0.00 Byte)
   _________________________________________________________________
8. Train Model
   For 30 Epochs
9. Virtualization Data
10. Save Model
11. Test Model
