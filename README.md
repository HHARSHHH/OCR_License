# OCR_License
This ML model extracts the License Number from the License plate. The first step is to detect the license plate with YOLO algorithm
then characters are segmented using OpenCV. Each segmented image is fed to the MobilenetV2 classifier model
then predictions are concatenated to form a License number.
Dataset link : https://drive.google.com/drive/folders/1zZK9NH1IXo9BiVYCKOaj0cEBeDs1sNUt?usp=sharing
