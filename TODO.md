
1. Generate 30 AI images for each animal category to create fake data
   1. C:\Users\igort\Documents\ComfyUI\output

2. Make a DataImporter class that can take a percentage of the real/AI images to include in its data loader
   1. Should be able to make any combo of real to AI, 0-100% each
3. Make a CNN model
4. Make a Combined model with ResNet50
   1. Coding tutorial 6
5. Optional: Make a Visual Transformer model
   1. Coding tutorial 10
6. Test baseline time to train each model on 30 real images per animal with CUDA
7. Hyperparam tune CNN
HAVE DONE BY **4/20**
1. Hyperparam tune Combined
   1. Freeze or not freeze pretrained? Check performance and time to train
2.  Optional: Hyperparam tune Visual Transformer
3.  Decide on grid of results (more like a line graph, left is real, right is AI):
   1.  (100 real, 0 AI), (100 real, 50 AI), (100 real, 100 AI), (50 real, 100 AI), (0 real, 100 AI)
4.  Train tuned models on these 5 combinations and record results on the 30 real test images for each animal
    1.  Metrics: basic accuracy, precision, recall, and F1-score (latter 3 to be averaged over each of the 90 classes)
HAVE DONE BY **4/25**

1.  Create poster and record presentation 4/28
2.  Write up final report 5/6
