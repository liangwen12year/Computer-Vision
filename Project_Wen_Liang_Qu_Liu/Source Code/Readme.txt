Before using the model, make sure all requirements below:
Nvidia GPU that support at least CUDA 8.0 and cuDNN 6.0.21 
Linux
Python2
Caffe2 (now included in Pytorch) that includes the Detectron module (https://github.com/facebookresearch/Detectron)

Our model is so big, so we can only put in the Google Drive, please download from: https://drive.google.com/open?id=1xfl1dE-AQ7WQZVkzp-iCh2-NfcrL3oD8

Usage:
cd {path_to_detectron}
python2 {path_to_the_testfile}/testfile.py \
--cfg {path_to_the_config_file}/faster_rcnn_R-50-FPN.yaml \
--output-dir {directory_that_receive_the_output} \
--image-ext jpg \
--wts {path_to_the_model}\model_final.pkl \
{directory_of_test_images}



