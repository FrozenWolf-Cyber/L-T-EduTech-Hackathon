# PS3 
**Description** -Description: Natural disasters and atmospheric anomalies demand remote monitoring and maintenance of naval objects especially big-size ships. For example, under poor weather conditions, prior knowledge about the ship model and type helps the automatic docking system process to be smooth. Thus, this set aims to classify the type of ships from an image data set of ships.

<table>
    <tr>
        <th rowspan="2">SNO</td>
        <th rowspan="2">Model</td>
        <th rowspan="2">Training loss</td>
        <th rowspan="2">Training accuracy</td>
        <th rowspan="2">Validation loss</td>
        <th rowspan="2">Validation accuracy</td>
        <th colspan="5">Precision</td>
        <th colspan="5">Recall</td>
        <th colspan="5">F1 Score</td>
        <th rowspan="2">Kappa</td>
        <th rowspan="2">Size(mb)</td>
    </tr>
    <tr>
        <td>Cargo</td>
        <td>Military</td>
        <td>Carrier</td>
        <td>Cruise</td>
        <td>Tanker</td>
        <td>Cargo</td>
        <td>Military</td>
        <td>Carrier</td>
        <td>Cruise</td>
        <td>Tanker</td>
        <td>Cargo</td>
        <td>Military</td>
        <td>Carrier</td>
        <td>Cruise</td>
        <td>Tanker</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>1</td>
        <td>resnet50</td>
        <td>0.0155044855898387</td>
        <td>99.547803617571</td>
        <td>0.30526700746268</td>
        <td>92.5</td>
        <td>0.90243902</td>
        <td>0.93333333</td>
        <td>1</td>
        <td>0.95454545</td>
        <td>0.82</td>
        <td>0.82222222</td>
        <td>0.93333333</td>
        <td>1</td>
        <td>0.93333333</td>
        <td>0.91111111</td>
        <td>0.86046512</td>
        <td>0.93333333</td>
        <td>1</td>
        <td>0.94382022</td>
        <td>0.86315789</td>
        <td>0.903333333333333</td>
        <td>94.39</td>
    </tr>
    <tr>
        <td>2</td>
        <td>vit_tiny_r_s16_p8_224</td>
        <td>0.000518766089389687</td>
        <td>99.9838501291989</td>
        <td>0.465771711990237</td>
        <td>91.25</td>
        <td>0.84615385</td>
        <td>0.9375</td>
        <td>1</td>
        <td>0.93333333</td>
        <td>0.8125</td>
        <td>0.73333333</td>
        <td>1</td>
        <td>1</td>
        <td>0.93333333</td>
        <td>0.86666667</td>
        <td>0.78571429</td>
        <td>0.96774194</td>
        <td>1</td>
        <td>0.93333333</td>
        <td>0.83870968</td>
        <td>0.883333333333333</td>
        <td>24.64</td>
    </tr>
    <tr>
        <td>3</td>
        <td>vit_tiny_patch16_224</td>
        <td>0.000258662122500031</td>
        <td>100</td>
        <td>0.284326805872842</td>
        <td>93.75</td>
        <td>1</td>
        <td>0.9375</td>
        <td>1</td>
        <td>1</td>
        <td>0.78947368</td>
        <td>0.73333333</td>
        <td>1</td>
        <td>1</td>
        <td>0.93333333</td>
        <td>1</td>
        <td>0.84615385</td>
        <td>0.96774194</td>
        <td>1</td>
        <td>0.96551724</td>
        <td>0.88235294</td>
        <td>0.916666666666666</td>
        <td>22.16</td>
    </tr>
    <tr>
        <td>4</td>
        <td>vit_small_patch8_224_dino</td>
        <td>3.42E-05</td>
        <td>100</td>
        <td>0.0970607578463386</td>
        <td>97.5</td>
        <td>0.93333333</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>0.93333333</td>
        <td>0.93333333</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>0.93333333</td>
        <td>0.93333333</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>0.93333333</td>
        <td>0.966666666666666</td>
        <td>86.74</td>
    </tr>
    <tr>
        <td>5</td>
        <td>vit_small_patch16_224</td>
        <td>0.000357729069072556</td>
        <td>100</td>
        <td>0.294432922825217</td>
        <td>96.25</td>
        <td>0.92857143</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>0.875</td>
        <td>0.86666667</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>0.93333333</td>
        <td>0.89655172</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>0.90322581</td>
        <td>0.95</td>
        <td>86.73</td>
    </tr>
    <tr>
      <td><b>* 6</b></td>
        <td><b><a href="https://github.com/FrozenWolf-Cyber/L-T-EduTech-Hackathon/blob/main/PS3/vit_base_patch8_224.ipynb">vit_base_patch8_224(sgd)</a></b></td>
        <td><b>5.43E-05</b></td>
        <td><b>100</td>
        <td><b>0.0298978400795022</b></td>
        <td><b>98.75</b></td>
        <td><b>0.95454545<</b>/td>
        <td><b>1</b></td>
        <td><b>1</b></td>
        <td><b>1</b></td>
        <td><b>0.93478261</b></td>
        <td><b>0.93333333</b></td>
        <td><b>1</b></td>
        <td><b>1</b></td>
        <td><b>1</b></td>
        <td><b>0.95555556</b></td>
        <td><b>0.94382022</b></td>
        <td><b>1</b></td>
        <td><b>1</b></td>
        <td><b>1</b></td>
        <td><b>0.94505495</b></td>
        <td><b>0.97</b></td>
        <td><b>343.3</b></td>
    </tr>
    <tr>
        <td>6a</td>
        <td>vit_base_patch8_224(adam)</td>
        <td>1.26545023194271</td>
        <td>46.2855297157622</td>
        <td>1.36305949687957</td>
        <td>33.6363636363636</td>
        <td>0.21568627</td>
        <td>0.42857143</td>
        <td>0.42857143</td>
        <td>0.125</td>
        <td>0.51111111</td>
        <td>0.48888889</td>
        <td>0.6</td>
        <td>0.06666667</td>
        <td>0.02222222</td>
        <td>0.51111111</td>
        <td>0.29931973</td>
        <td>0.5</td>
        <td>0.11538462</td>
        <td>0.03773585</td>
        <td>0.51111111</td>
        <td>0.227777777777777</td>
        <td>343.3</td>
    </tr>
    <tr>
        <td>7</td>
        <td>vit_base_patch16_224</td>
        <td>5.04E-05</td>
        <td>100</td>
        <td>0.0669359442894347</td>
        <td>97.5</td>
        <td>0.93333333</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>0.93333333</td>
        <td>0.93333333</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>0.93333333</td>
        <td>0.93333333</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>0.93333333</td>
        <td>0.966666666666666</td>
        <td>343.27</td>
    </tr>
    <tr>
        <td>8</td>
        <td>vit_large_patch16_224</td>
        <td>0.000314225390369969</td>
        <td>99.9838187702265</td>
        <td>0.186438377808216</td>
        <td>96.9298245614035</td>
        <td>0.93333333</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>0.93333333</td>
        <td>0.93333333</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>0.93333333</td>
        <td>0.93333333</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>0.93333333</td>
        <td>0.973099415204678</td>
        <td>1.21gb</td>
    </tr>
</table>

Among multiple models ```vit_base_patch8_224(sgd)``` stood out in performance with a kappa score of **0.97** on validation set.

**Note:** _The validation set was split evenly from the train set such that all classes were balanced out, and since there was no test set to find the kappa value, we used this validation dataset which was kept unseen from the model._
## Best model performance:
Model name: ```vit_base_patch8_224```
#### Validation Performance: 
``` VALIDATION LOSS for EPOCH 30 : 0.029897840079502202
  VALIDATION PREC : [0.95454545 1.         1.         1.         0.93478261]
  RECALL : [0.93333333 1.         1.         1.         0.95555556]
  F1 : [0.94382022 1.         1.         1.         0.94505495]  
  ACC : 98.75  KAPPA : 0.97
```
![ps3_Acc](https://user-images.githubusercontent.com/57902078/212664245-39f89e7b-c5fa-41dd-9653-b1ff1af86822.png)
![ps3_f1](https://user-images.githubusercontent.com/57902078/212664249-1429297a-9ee1-4f19-8055-4c7a06d37836.png)
![ps3_kappa](https://user-images.githubusercontent.com/57902078/212664252-ab5f5c00-0947-4a58-9a1e-648a1bb0df46.png)
![ps3_loss](https://user-images.githubusercontent.com/57902078/212664255-d67a0069-6909-40da-a787-635da393f6f1.png)
![ps3_prec](https://user-images.githubusercontent.com/57902078/212664260-82b486c8-09d6-4eea-af8f-37e95e594303.png)
![ps3_recall](https://user-images.githubusercontent.com/57902078/212664268-0c3c6ece-af3b-4f61-89da-2913cccd72b3.png)

## Experimentation & Observation:

We started exploring the dataset and started fine-tuning the given dataset on the standard pre-trained model such as Resnet, VGG16, Efficientnet-B7, and Vision Transformers (ViT). After multiple runs, we found that ViT models outperformed all other models with/without augmentation and performed exceptionally well using the SGD optimizer in particular. Image augmentation, such as random rotation and flips, did not help in improving the model performance, and the model was able to generalize well without overfitting without any image augmentation.
All the models were trained using Kaggle GPU and partially locally.
