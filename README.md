# image-adversarial-sample
1. Datasets 
This paper has not been officially published yet, so the current program is provided for testing purposes only. Once the paper is accepted, we will upload the complete infrared image dataset. Currently, we have included a few enhanced infrared images in the `flickr30k-images` folder for testing purposes.  

2. Preparing Model Checkpoints  
The models used in the paper are open-source. Due to the large file size, you can obtain them directly from their respective official repositories. Below are three example links:  
- https://github.com/salesforce/BLIP  
- https://github.com/uta-smile/TCL  
- https://github.com/openai/CLIP  
...

3. Adversarial Sample Generation 
We provide `eval.py`, where you can choose to import SGAttacker, VLAttacker, or V-FSARAttacker for evaluating the performance of image-text retrieval attacks. Additionally, the perturbation layer images are displayed separately. After running the program, they will be displayed sequentially.

4. **Transfer Attacks on Large Language Models (LLMs)  
Send adversarial images to LLMs and prompt the system with the query "Describe this image".

5. Visualization  
The code for generating attention heatmaps will be uploaded later if needed. Adversarial samples and perturbation layer images will be displayed successively after running the `eval.py` file.  
