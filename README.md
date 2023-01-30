# Trinity-Net
Trinity-Net: Gradient-Guided Swin Transformer-based Remote Sensing Image Dehazing and Beyond.
This is the code of the implementation of the Trinity-Net.

# Requirement
ubuntu, torch==1.8.1+cu111, torchvision==0.9.1+cu111, tensorboardX==2.5.1.

# Training
1. Put the training data to corresponding folders (hazy image to ./data/train_data/input, GT to ./data/train_data/target)
2. Hyperparameter (./Enh_opt)
3. Python Enh_train.py

# Testing
1. Put the testing data to corresponding folders (hazy image to ./data/test_data/input, GT to ./data/test_data/target, GT for full-reference evaluation, such as PSNR and SSIM)
2. Python Enh_eval.py
3. Find the result in corresponding folder (./checkpoints/XX/test_results)

# Remote Sensing Image Dehazing Dataset (RSID)
Download RSID from Baidu Cloud: https://pan.baidu.com/s/1zzk1KiKJHnZPHg4BV5U7dA?pwd=1004 key: 1004 or Google Drive: https://drive.google.com/file/d/1FC7oSkGTthjHl2sKN-yGrKhssgV0QB4F/view?usp=sharing

# Natural Image Dehazing Dataset (NID)
Download NID from Baidu Cloud: https://pan.baidu.com/s/1x085oHJ_o1MlKCB1ktVXlg?pwd=1004 key: 1004 or Google Drive: https://drive.google.com/file/d/1uYyav5fBGdJcZ1XsxdMqXTFwdc-6E82V/view?usp=sharing

# Contact Us
If you have any questions, please contact us (chikaichen@mail.nwpu.edu.cn).
