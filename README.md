# Infrared-image-adversarial-sample

![image](https://github.com/user-attachments/assets/253103d3-dfba-425d-9c39-bdd67b93773c)

Method framework

1. Datasets 
This paper has not been officially published yet, so the current program is provided for testing purposes only. Once the paper is accepted, we will upload the complete infrared image dataset. Currently, we have included a few enhanced infrared images in the `flickr30k-images` folder for testing purposes.  infrared image enhancement.py integrates low-light image information into infrared images. After running the script, you can observe the enhanced results.

![image](https://github.com/user-attachments/assets/4b5b02ea-0bff-46fd-84c8-a89a9f0fb32f)

3. Preparing Model Checkpoints  
The models used in the paper are open-source. Due to the large file size, you can obtain them directly from their respective official repositories. Below are three example links:  
- https://github.com/salesforce/BLIP  
- https://github.com/uta-smile/TCL  
- https://github.com/openai/CLIP  
...

![1731903310468](https://github.com/user-attachments/assets/a04840d2-f172-4522-ac75-3451fbb8208b)

V-FSA(ours) vs SGA与VLA

3. Adversarial Sample Generation 
We provide `eval.py`, where you can choose to import SGAttacker, VLAttacker, or V-FSARAttacker for evaluating the performance of image-text retrieval attacks. Additionally, the perturbation layer images are displayed separately. After running the program, they will be displayed sequentially.
![image](https://github.com/user-attachments/assets/ac07608e-aa00-418d-bde0-5f77041b957c)


4. Transfer Attacks on Large Language Models (LLMs)  
Send adversarial images to LLMs and prompt the system with the query "Describe this image".

5. Visualization  
The code for generating attention heatmaps will be uploaded later if needed. Adversarial samples and perturbation layer images will be displayed successively after running the `eval.py` file.  
![1731900090143](https://github.com/user-attachments/assets/13c6cafd-9682-45a9-a670-516c60b569c3)
