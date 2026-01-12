Semantic Image Segmentation is a deep learning project that performs pixel-level classification on urban scene images using a U-Net architecture. Trained on the CamVid dataset, the model learns to segment roads, buildings, vehicles, pedestrians, and other scene elements for fine-grained visual understanding.



#### **Key Achievements**



* Built an end-to-end semantic segmentation pipeline using TensorFlow and tf.data.



* Trained a U-Net model on resized CamVid images for multi-class pixel prediction.



* Evaluated model performance using accuracy and Mean Intersection over Union (IoU).



* Visualized input images, ground truth masks, and predicted segmentation outputs.



#### **Technical Highlights**



* Model Architecture: U-Net with encoder–decoder structure and skip connections.



* Frameworks \& Tools: TensorFlow/Keras, Python, Google Colab, Matplotlib.



* Training Setup: Adam optimizer, sparse categorical crossentropy, early stopping, model checkpointing.



* Data Handling: Custom image–mask loading, normalization, batching, and prefetching with tf.data.
