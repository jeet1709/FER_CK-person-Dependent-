# FER_CKplus_Person_Dependent
Facial Expression Recognition model trained on CK+ dataset with Person Dependent training-testing

- 10 Fold Cross Validation used for training testing.
- Using Transfer Learning on VGG16 model with last three layer set to trainable with top layer included.
- Model is trained for **15 EPOCHS**
- Optimizer used is Adam and Learning Rate is 0.001
- Loss function used is **categorical_crossentropy**
