# PS1 
**Description** - Concrete cracking is a major issue in Bridge Engineering. Detection of cracks facilitates the design, construction and maintenance of bridges effectively.

<table>
    <tr>
        <th  rowspan="2">SNO</th>
        <th rowspan="2">Model</td>
        <th rowspan="2">Training loss</td>
        <th rowspan="2">Training accuracy</td>
        <th rowspan="2">Validation loss</td>
        <th rowspan="2">Validation accuracy</td>
        <th  rowspan="2">Test Loss</td>
        <th  rowspan="2">Test Accuracy</td>
        <th colspan="2"  >Precision</td>
        <th colspan="2" >Recall</td>
        <th colspan="2" >F1 Score</td>
        <th colspan="2">Support</td>
        <th rowspan="2" rowspan="2">Size(mb)</td>
    </tr>
    <tr>
        <td>Positive</td>
        <td>Negative</td>
        <td>Positive</td>
        <td>Negative</td>
        <td>Positive</td>
        <td>Negative</td>
        <td>Positive</td>
        <td>Negative</td>
    </tr>
    <tr>
        <th>1</th>
        <td>vit_tiny_r_s16_p8_224</td>
        <td>0.000554299960640491</td>
        <td>100</td>
        <td>0.0162891943918321</td>
        <td>98.5576923076923</td>
        <td>0.0168405814239612</td>
        <td>100</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>100</td>
        <td>100</td>
        <td>24.64</td>
    </tr>
    <tr>
        <th>1a</th>
        <td>vit_tiny_r_s16_p8_224(adam)</td>
        <td>8.65E-06</td>
        <td>100</td>
        <td>0.341207414359325</td>
        <td>96.1538461538461</td>
        <td>1.32988578424848</td>
        <td>84.1346153846153</td>
        <td>0.75757576</td>
        <td>1</td>
        <td>1</td>
        <td>0.68</td>
        <td>0.86206897</td>
        <td>0.80952381</td>
        <td>100</td>
        <td>100</td>
        <td>24.64</td>
    </tr>
    <tr>
        <th><b>* 2</b></th>
        <td><b><a href="https://github.com/FrozenWolf-Cyber/L-T-EduTech-Hackathon/blob/main/PS1/vit_tiny_patch16_224.ipynb">vit_tiny_patch16_224</a></b></td>
        <td><b>0.000391737806766238</b></td>
        <td><b>100</b></td>
        <td><b>0.0066456968404684</b></td>
        <td><b>100</b></td>
        <td><b>0.00862143541542956</b></td>
        <td><b>100</b></td>
        <td><b>1</b></td>
        <td><b>1</b></td>
        <td><b>1</b></td>
        <td><b>1</b></td>
        <td><b>1</b></td>
        <td><b>1</b></td>
        <td><b>100<</b>/td>
        <td><b>100</b></td>
        <td><b>24.64</b></td>
    </tr>
    <tr>
        <th>3</th>
        <td>vit_small_patch8_224_dino</td>
        <td>0.000114268117565523</td>
        <td>100</td>
        <td>0.000981450813504544</td>
        <td>100</td>
        <td>0.00134592478011304</td>
        <td>100</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>100</td>
        <td>100</td>
        <td>86.74</td>
    </tr>
    <tr>
        <th>4</th>
        <td>vit_small_patch16_224</td>
        <td>0.00109570801348462</td>
        <td>100</td>
        <td>0.0165256364203882</td>
        <td>99.0384615384615</td>
        <td>0.0172053847032097</td>
        <td>100</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>100</td>
        <td>100</td>
        <td>86.72</td>
    </tr>
    <tr>
        <th>5</th>
        <td>vit_base_patch8_224</td>
        <td>2.34E-05</td>
        <td>100</td>
        <td>0.0109473363600591</td>
        <td>99.5</td>
        <td>0.0298415567417396</td>
        <td>99</td>
        <td>1</td>
        <td>0.98039216</td>
        <td>0.98</td>
        <td>1</td>
        <td>0.98989899</td>
        <td>0.99009901</td>
        <td>100</td>
        <td>100</td>
        <td>343.3</td>
    </tr>
    <tr>
        <th>6</th>
        <td>vit_base_patch16_224</td>
        <td>2.89E-05</td>
        <td>100</td>
        <td>0.000303537664754003</td>
        <td>100</td>
        <td>0.000899293540896906</td>
        <td>100</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>100</td>
        <td>100</td>
        <td>343.26</td>
    </tr>
    <tr>
        <th>7</th>
        <td>vit_large_patch16_224</td>
        <td>0.000131708909235233</td>
        <td>100</td>
        <td>0.00477138461696085</td>
        <td>100</td>
        <td>0.0421330400995793</td>
        <td>99.5</td>
        <td>1</td>
        <td>0.99009901</td>
        <td>0.99</td>
        <td>1</td>
        <td>0.99497487</td>
        <td>0.99502488</td>
        <td>100</td>
        <td>100</td>
        <td>1.21gb</td>
    </tr>
</table>

Among multiple models ```vit_tiny_patch16_224``` stood out in performance while being relatively very small with just **24.64**

## Best model performance:
Model name: ```vit_tiny_patch16_224```
#### Test Performance: 
```LOSS : 0.008621435415429564  ACCURACY : 100.0
TEST PREC: [1. 1.] RECALL: [1. 1.] F1 SCORE: [1. 1.] SUPPORT: [100 100]
```
![ps1_train_loss](https://user-images.githubusercontent.com/57902078/212643768-df338cdf-c168-4927-9c8d-36b6b49107c2.png)
![ps1_acc](https://user-images.githubusercontent.com/57902078/212643921-f3e223c9-f9fa-4d46-be00-e8ca7e10474c.png)
![ps1_f1](https://user-images.githubusercontent.com/57902078/212644035-16846980-b647-418d-a7db-7e0dfb157f86.png)
![ps1_prec](https://user-images.githubusercontent.com/57902078/212644438-2caa44ec-81ee-4fbd-9817-9575dde06b3e.png)
![ps1_recall](https://user-images.githubusercontent.com/57902078/212644453-551bba79-80bb-4542-8235-4de5c65c7851.png)

## Experimentation & Observation:

We started exploring the dataset and started fine-tuning the given dataset on the standard pre-trained model such as Resnet, VGG16, Efficientnet-B7, and Vision Transformers (ViT). After multiple runs, we found that ViT models outperformed all other models with/without augmentation and performed exceptionally well using the SGD optimizer in particular. Image augmentation, such as random rotation and flips, did not help in improving the model performance, and the model was able to generalize well without overfitting without any image augmentation.
All the models were trained using Kaggle GPU and partially locally.
