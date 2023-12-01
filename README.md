# GA_SIM
Prepare data

# Prepare data
Step1: prepare SentiCap img generate_senticapimg.py
Step2: generate resnet features for all used images generate_resnet_feat.py
Step3: prepare objects vocabulary using VG dataset's object labels generate_objectvocab.py
Step4: prepare data of FlcikrStyle and SentiCap prepro_flickrstyledata.py & prepro_senticapdata.py
Step5: construct train/val/test data generate_dataset.py
Step6: prepare for calculating PPL using SRILM generate_srilm.py, reference: https://blog.csdn.net/u011500062/article/details/50781101, https://ynuwm.github.io/2017/05/24/SRILM训练语言模型实战/, http://www.mamicode.com/info-detail-1944347.html
Step7: build vocab build_vocab.py
Step8: prepare json file for pycocoeval generate_cocoeval.py
