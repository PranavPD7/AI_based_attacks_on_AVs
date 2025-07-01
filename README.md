This repository contains implementations for a shapeshifter based adversarial attack and a backdoor attack for traffic sign dataset.
This demonstrates the vulnerabilities of object detectors like YOLO and image classifiers like resnet which are used in autonomous vehicles 

## Steps to execute the code

1. Clone repository (in colab or locally)

2. Install the required libraries
  <pre><code> !pip install torch torchvision tqdm numpy </code></pre>

3. Move to ```Backdoor Defense``` Repository
    
4. Run the data_loader.py and defense.py files
   <pre> <code> !python dataloader.py </code> </pre>

   <pre> <code> !python defense.py </code> </pre>



