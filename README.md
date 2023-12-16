# Neural Style Transfer Study - from image collections to video, from VGG to diffusion

**Authors:** Group 38  - Binbin Chen, Jingqi Yao, Yuan Zhang

**Final Report:** CS581_NST_FinalReport_Group38.pdf

**Video Demo:** https://drive.google.com/drive/folders/1ooBUJVS92jDuYri2bFwRnWsB0zl2wPgN?usp=sharing
- short version within 3 minutes: demo-short.mov
- normal version with 4.5 minutes: demo-normal.mov

**Result Link:** https://drive.google.com/drive/folders/1ooBUJVS92jDuYri2bFwRnWsB0zl2wPgN?usp=sharing

## Main Contributions

- conducted elaborate **comparison experiments** among different backbones, neural architectures, and models
  - including: VGG, ResNet, AlexNet, Fast Style Transfer, Multimodal style transfer, CycleGAN, and Diffusion
- provided **evaluation metrics** towards 1. model performance (effectiveness for style and coherence for content) and 2. model efficiency 
  - based on FID, CLIP, Contour Detection, User Ranking
  - training time, memory allocation
- fine-tuned models to generate single-image style transfer, **image collection** style transfer and **video** style transfer
- maintained model robustness with large images and videos



## Code Instructions

- **note**: 

  - There're some movements of files and re-organization of folders for unable to upload the large contents, so you have to change some path and uncomment some code or use Google Drive link for full usage.
  - Some dependent package installations are embedded into the .ipynb files.

- For CycleGANs, run this code for single-image, image collection, video style transfer inference:

  - ```bash
    cd Final_NST
    run CycleGAN_MM.ipynb manually or//
    jupyter nbconvert --to notebook --execute CycleGAN_MM.ipynb
    
    or use link: https://drive.google.com/drive/folders/12AO05ejrW7C1L5rjtNTET9_5HiDYTCFE?usp=sharing
    ```

- For Diffusion, run this code for single-image style transfer inference:

  - ```bash
    cd Final_NST
    run InST.ipynb manually or//
    jupyter nbconvert --to notebook --execute InST.ipynb
    
    or use link: https://drive.google.com/drive/folders/1SviDT_2KiZ9m5NA3keqPlJ2pEvdXLOM7?usp=sharing
    ```

- For VGG19, run this code for single-image style transfer inference:

  - ```bash
    cd Final_NST
    run VGG19.ipynb manually or//
    jupyter nbconvert --to notebook --execute VGG19.ipynb
    ```
    
- For Fast Style Transfer, run this code for single-image style transfer inference:

  - ```bash
    cd Final_NST
    run Fast_Style_Transfer_for_Arbitrary_Styles.ipynb manually or//
    jupyter nbconvert --to notebook --execute Fast_Style_Transfer_for_Arbitrary_Styles.ipynb
    ```

- For AlexNet, run this code for single-image style transfer inference:

  - ```bash
    cd Final_NST
    run AlexNet1206.ipynb manually or//
    jupyter nbconvert --to notebook --execute AlexNet1206.ipynb
    ```
- For MST, run this code for single-image style transfer inference:

  - ```bash
    use link: [https://drive.google.com/drive/folders/12AO05ejrW7C1L5rjtNTET9_5HiDYTCFE?usp=sharing](https://drive.google.com/drive/folders/1TV7auFaVm9YubetFQ_EizncI8-CLVOfL?usp=sharing)
    ```
  
- For model evaluation, run this code:

  - ```bash
    cd Final_NST
    run evaluator.ipynb manually or//
    jupyter nbconvert --to notebook --execute evaluator.ipynb
    
    or use link: https://drive.google.com/drive/folders/1oUbQeC3QRc8qlVjvjI-0dg8c8GEYnhlP?usp=sharing
    ```
    evaluator_Yuan.ipynb contains evaluation code blocks and results for some models, but evaluator.ipynb itself works for all.
    
