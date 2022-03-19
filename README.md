# MaskDetector
YOLOV3 model to detect mask breachers
# Dataset collected from
link1 : https://www.kaggle.com/datasets/ashwingupta3012/human-faces
<br /> link2 : https://www.kaggle.com/datasets/andrewmvd/face-mask-detection

# configutations
in the configuration file we made changes at certain points considering two classes <br />
filters = (number of classes+5)*3 <br />
using this for two classes filters = 21 <br />

similiarly classes = 2 <br />
And using the derivation for max-bathces as classes*2000
<br /> we update it to 2*2000=4000 <br />

we use the activators to be mish and sigmoid <br />
