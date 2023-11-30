# Physical_Adversary_Attack

First, we cause an untargeted misclassification of the provided traffic sign image (benign_xx.png) optimized for the position of the adversarial patch (meaning optimized for the location of the patch in the traffic sign surface). The task is completed if the script causes misclassification of the traffic sign image (meaning the traffic sign is not recognized anymore as the original correct prediction given by the 1st shell). This can be tested in the next shell.

Next the script causes targeted misclassification of your provided traffic sign image (benign_xx.png) optimized for the position of the adversarial patch (meaning optimized for the location of the patch in the traffic sign surface). For the purpose of this project I use the class with label ‘40’ which is the ‘Roundabout Mandatory’ sign per the classes classified in the script.

Lastly the script generates an adversarial attack on the 50 km/hr traffic sign image. Here we include the size of the patch as parameters for optimization to minimize the size of the patch where prompted (meaning optimized for minimizing the dimension of the patch in the traffic sign surface). I modify the patch size to minimize and misclassify the image. 
