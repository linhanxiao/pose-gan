## RE-ID experiment 
1. Download generated [images](https://yadi.sk/d/8quChtr63Raeof)
2. For IDE baseline: clone repository https://github.com/zhunzhong07/IDE-baseline-Market-1501.

2.1 Replace market_evaluation/dataset/train.txt with train.txt from this folder.

2.2 Increase number of iteration to 200k (and step to 90k) in models/market/ResNet_50/ResNet_50_solver.prototxt

2.3 Follow the instructions for ResNet50.

3. For discriminative embeding: clone repository https://github.com/AliaksandrSiarohin/caffe-reid and follow the instructions for resnet50.



## Images from paper
Names of the images from paper can be found in cases. This images is searched in dataset using ```search.py```.
User study images is in fashion-userstydy and market-userstudy.
