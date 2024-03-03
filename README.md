
Kidney Segmentation

This project aimed to develop a CNN segmentation model for visualizing blood vessel segmentations in kidney scans. Leveraging a segmentation approach, we participated in a Kaggle competition aimed at training models to accurately segment blood vessels from kidney scans.

The dataset was obtained from the Kaggle website, requiring minimal preprocessing steps. Images were loaded from the files, shuffled, and subsequently used for training.

We employed a U-Net architecture comprising approximately 800,000 parameters. While a transfer learning approach was initially considered, it was deemed ineffective. As a result, the decision was made to train the U-Net model from scratch.

The "Kidney Code" file encompasses all preprocessing and training steps, detailing the entire process.

In the final stage, the model's performance was evaluated, and the output was converted to the Run-Length Encoding (RLE) format, necessary for submission on Kaggle.

Notably, the model achieved an impressive accuracy rate of approximately 98%. However, it's important to mention that the testing code is not included in the uploaded files.
