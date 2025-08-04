# CCC-Cross-modal-Contrastive-Creator-for-End-to-End-Sign-Language-Generation

This is the project homepage for the paper "CCC: Cross-modal Contrastive Creator for End-to-End Sign Language Generation". On this homepage, we provide the code used in the paper and a demonstration of the sign language generation results.

To view the sign language generation demo, please visit:
https://pretty-natural-satyr.ngrok-free.app

Phoenix14T Dataset:
https://www-i6.informatik.rwth-aachen.de/~koller/RWTH-PHOENIX-2014-T/

Model Evaluation: https://github.com/neccam/slt

After downloading the dataset, skeletal joint points need to be extracted using RTMPose. This can be easily accomplished using the MMPose project:
https://github.com/open-mmlab/mmpose

We recommend using the pre-trained model of the RTMPose-w variant. The extracted skeletal keypoints are simplified sequentially through the following code：dataset/Simplify/1-add-number.py，2-delete-additional-number.py，3-delete-all-number.py

