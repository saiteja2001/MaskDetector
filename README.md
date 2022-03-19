# MaskDetector
YOLOV3 model to detect mask breachers
# Dataset collected from
link1 : https://www.kaggle.com/datasets/ashwingupta3012/human-faces
link2 : https://www.kaggle.com/datasets/andrewmvd/face-mask-detection

# configutations
in the configuration file we made changes at certain points considering two classes
filters = (number of classes+5)*3
using this for two classes filters = 21

similiarly classes = 2
And using the derivation for max-bathces as classes*2000 we update it to 2*2000=4000

we use the activators to be mish and sigmoid
