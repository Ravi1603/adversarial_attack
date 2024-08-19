# Adversarial-Patch-Attack
This is the code for the adversarial patch attack on the EuroSAT dataset. 

What is an adversarial attack?
As AI/ML usage rapidly increases, ensuring the reliability of these models becomes crucial. Numerous attacks have been developed that can cause models to be classified wrongly, which could have catastrophic consequences, such as in the context of self-driving cars. Therefore, significant research is being conducted to enhance the robustness of machine learning models against these attacks.

Adversarial attack: an attack that aims to cause an AI system to make a mistake or misclassification, often through subtle manipulations of the input data.

EuroSAT dataset - The dataset is based on Sentinel-2 satellite images covering 13 spectral bands and consisting of 10 classes with a total of 27,000 labeled and geo-referenced images. 
Class Names: 'AnnualCrop', 'Forest', 'HerbaceousVegetation', 'Highway', 'Industrial', 'Pasture', 'PermanentCrop', 'Residential', 'River', 'SeaLake'.


![image](https://github.com/user-attachments/assets/dcfc17ea-0744-44e7-b47d-8db32d7285cb)

Example of predictions - The model's efficiency is 93.07%.
![image](https://github.com/user-attachments/assets/5fb2aca9-a717-4f9e-b0ea-7a37fb6eea86)

Example of FGSM(noise) attack - The model's efficiency after this attack is 27%.
![image](https://github.com/user-attachments/assets/5da49582-b0a4-40d5-aa7e-a28dda070c0d)

Example of patch attack - The model's efficiency after this attack is almost 3%.
![image](https://github.com/user-attachments/assets/b3ab03b5-18a2-4094-8610-54c33ea24f37)



