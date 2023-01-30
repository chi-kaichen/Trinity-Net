# Trinity-Net
Trinity-Net: Gradient-Guided Swin Transformer-based Remote Sensing Image Dehazing and Beyond.
This is the code of the implementation of the Trinity-Net.

# Requirement
ubuntu, TensorFlow 1.x, keras==2.3.1, numpy==1.16.1.

# Testing
1. Download the checkpoint from Baidu Cloud: https://pan.baidu.com/s/1cCPWxGtRCEEEStynMWK0AQ?pwd=1004 key: 1004 or Google Drive: https://drive.google.com/file/d/1QMmvPohnLgqDZ5A3wZ7SlGHPN3r4WzK1/view?usp=sharing and put it in FPGAN folder.
2. Download the VGG-pretrained model from Baidu Cloud: https://pan.baidu.com/s/1NvZRtsxy7MPaf73vMj2E4w?pwd=1004 key: 1004 or Google Drive: https://drive.google.com/file/d/1R_7559x3_WhOxiqoeNkbcnc4E1_bILXv/view?usp=sharing and put it in FPGAN folder.
3. Put the inputs to corresponding folders (raw underwater image to ./Finally2/A, medium transmission to ./Finally2/WB)
4. Python main.py (model: default = 'inference')
5. Find the result in Test folder.

# Underwater Image Dehazing Benchmark (UIDB)
Download UIDB from Baidu Cloud: https://pan.baidu.com/s/1x085oHJ_o1MlKCB1ktVXlg?pwd=1004 key: 1004 or Google Drive: https://drive.google.com/file/d/1uYyav5fBGdJcZ1XsxdMqXTFwdc-6E82V/view?usp=sharing

# Contact Us
If you have any questions, please contact us (chikaichen@mail.nwpu.edu.cn).
