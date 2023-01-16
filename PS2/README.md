# PS2 
**Description** - Power outages in the power distribution systems are extremely expensive. Substation issues include

- Equipment repair and replacement
- Less system reliability
- Wildlife reach in the open areas of substations

Here the solution aims at detecting the various objects of the substation for monitoring and maintenance purposes.

<table>
    <tr>
        <th  rowspan="2">SNO</td>
        <th  rowspan="2">Model</td>
        <th  rowspan="2">Training loss</td>
        <th  rowspan="2">Training accuracy</td>
        <th  rowspan="2">Validation loss</td>
        <th  rowspan="2">Validation accuracy</td>
        <th  rowspan="2">Loss</td>
        <th  rowspan="2">Accuracy_best</td>
        <th colspan="3">Precision</td>
        <th colspan="3">Recall</td>
        <th colspan="3">F1 Score</td>
        <th colspan="3">Support</td>
        <th  rowspan="2">Kappa</td>
        <th rowspan="2">Size(mb)</td>
    </tr>
    <tr>
        <td>Surge Arrestor</td>
        <td>Transformer</td>
        <td>Transformer with Surge Arrestor</td>
        <td>Surge Arrestor</td>
        <td>Transformer</td>
        <td>Transformer with Surge Arrestor</td>
        <td>Surge Arrestor</td>
        <td>Transformer</td>
        <td>Transformer with Surge Arrestor</td>
        <td>Surge Arrestor</td>
        <td>Transformer</td>
        <td>Transformer with Surge Arrestor</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>1</td>
        <td>vit_tiny_r_s16_p8_224</td>
        <td>0.0225348259555175</td>
        <td>99.4791666666666</td>
        <td>1.20923614501953</td>
        <td>66.6666666666666</td>
        <td>0.377547923475503</td>
        <td>89.0625</td>
        <td>0.78947368</td>
        <td>0.9375</td>
        <td>0.89473684</td>
        <td>0.83333333</td>
        <td>0.83333333</td>
        <td>0.94444444</td>
        <td>0.81081081</td>
        <td>0.81081081</td>
        <td>0.91891892</td>
        <td>18</td>
        <td>18</td>
        <td>18</td>
        <td>0.805555555555555</td>
        <td>24.64</td>
    </tr>
    <tr>
        <td>2</td>
        <td>vit_tiny_patch16_224</td>
        <td>0.0177038602996617</td>
        <td>98.9583333333333</td>
        <td>0.967087268829345</td>
        <td>75</td>
        <td>0.401243545114994</td>
        <td>81.7708333333333</td>
        <td>0.76470588</td>
        <td>0.8</td>
        <td>0.88235294</td>
        <td>0.72222222</td>
        <td>0.88888889</td>
        <td>0.83333333</td>
        <td>0.74285714</td>
        <td>0.84210526</td>
        <td>0.85714286</td>
        <td>18</td>
        <td>18</td>
        <td>18</td>
        <td>0.722222222222222</td>
        <td>22.16</td>
    </tr>
    <tr>
        <td>3</td>
        <td>vit_small_patch8_224_dino</td>
        <td>0.0191240947363742</td>
        <td>98.9583333333333</td>
        <td>0.354451566934585</td>
        <td>91.6666666666666</td>
        <td>0.413140682503581</td>
        <td>81.7708333333333</td>
        <td>0.72222222</td>
        <td>0.85</td>
        <td>0.875</td>
        <td>0.72222222</td>
        <td>0.94444444</td>
        <td>0.77777778</td>
        <td>0.72222222</td>
        <td>0.89473684</td>
        <td>0.82352941</td>
        <td>18</td>
        <td>18</td>
        <td>18</td>
        <td>0.722222222222222</td>
        <td>86.74</td>
    </tr>
    <tr>
        <td>4</td>
        <td>vit_small_patch16_224</td>
        <td>0.0229812290053814</td>
        <td>98.9583333333333</td>
        <td>0.567398607730865</td>
        <td>75</td>
        <td>0.31965248286724</td>
        <td>83.3333333333333</td>
        <td>0.8</td>
        <td>0.77272727</td>
        <td>0.94117647</td>
        <td>0.66666667</td>
        <td>0.94444444</td>
        <td>0.88888889</td>
        <td>0.72727273</td>
        <td>0.85</td>
        <td>0.91428571</td>
        <td>18</td>
        <td>18</td>
        <td>18</td>
        <td>0.75</td>
        <td>86.72</td>
    </tr>
    <tr>
  <td><b>* 5</b></td>
        <td><b><a href="https://github.com/FrozenWolf-Cyber/L-T-EduTech-Hackathon/blob/main/PS2/vit_base_patch8_224.ipynb">vit_base_patch8_224(sgd)</a></b></td>
        <td><b>0.0134351163142127</b></td>
        <td><b>98.8888888888888</b></td>
        <td><b>1.07717802127202</b></td>
        <td><b>58.3333333333333</b></td>
        <td><b>0.220577826648617</b></td>
        <td><b>92.8571428571428</b></td>
        <td><b>0.88888889</b></td>
        <td><b>0.94444444</b></td>
        <td><b>0.94444444</b></td>
        <td><b>0.88888889</b></td>
        <td><b>0.94444444</b></td>
        <td><b>0.94444444</b></td>
        <td><b>0.88888889</b></td>
        <td><b>0.94444444</b></td>
        <td><b>0.94444444</b></td>
        <td><b>18</b></td>
        <td><b>18</b></td>
        <td><b>18</b></td>
        <td><b>0.888888888888888</b></td>
        <td><b>343.3</b></td>
    </tr>
    <tr>
        <td>5a</td>
        <td>vit_base_patch8_224(adam)</td>
        <td>1.22904528545008</td>
        <td>50</td>
        <td>1.18211032946904</td>
        <td>50</td>
        <td>1.16420696462903</td>
        <td>44.6428571428571</td>
        <td>0.27272727</td>
        <td>0.40740741</td>
        <td>0.625</td>
        <td>0.16666667</td>
        <td>0.61111111</td>
        <td>0.55555556</td>
        <td>0.20689655</td>
        <td>0.48888889</td>
        <td>0.58823529</td>
        <td>18</td>
        <td>18</td>
        <td>18</td>
        <td>0.166666666666666</td>
        <td>343.3</td>
    </tr>
    <tr>
        <td>6</td>
        <td>vit_base_patch16_224</td>
        <td>0.0138681949919878</td>
        <td>99.4444444444444</td>
        <td>1.38310711582501</td>
        <td>75</td>
        <td>0.315895141800865</td>
        <td>85.7142857142857</td>
        <td>0.77777778</td>
        <td>0.88888889</td>
        <td>0.88888889</td>
        <td>0.77777778</td>
        <td>0.88888889</td>
        <td>0.88888889</td>
        <td>0.77777778</td>
        <td>0.88888889</td>
        <td>0.88888889</td>
        <td>18</td>
        <td>18</td>
        <td>18</td>
        <td>0.777777777777777</td>
        <td>343.26</td>
    </tr>
    <tr>
        <td>7</td>
        <td>vit_large_patch14_224</td>
        <td>0.949684994750552</td>
        <td>53.3333333333333</td>
        <td>1.11181551218032</td>
        <td>58.3333333333333</td>
        <td>1.00124096231801</td>
        <td>53.5714285714285</td>
        <td>0.48148148</td>
        <td>0.53846154</td>
        <td>0.64285714</td>
        <td>0.72222222</td>
        <td>0.38888889</td>
        <td>0.5</td>
        <td>0.57777778</td>
        <td>0.4516129</td>
        <td>0.5625</td>
        <td>18</td>
        <td>18</td>
        <td>18</td>
        <td>0.305555555555555</td>
        <td>1.21gb</td>
    </tr>
    <tr>
        <td>8</td>
        <td>vit_large_patch16_224(batch_size4)</td>
        <td>0.0184153128463852</td>
        <td>99.4444444444444</td>
        <td>1.32563134034474</td>
        <td>66.6666666666666</td>
        <td>0.415346324234893</td>
        <td>85.7142857142857</td>
        <td>0.78947368</td>
        <td>0.84210526</td>
        <td>0.9375</td>
        <td>0.83333333</td>
        <td>0.88888889</td>
        <td>0.83333333</td>
        <td>0.81081081</td>
        <td>0.86486486</td>
        <td>0.88235294</td>
        <td>18</td>
        <td>18</td>
        <td>18</td>
        <td>0.777777777777777</td>
        <td>1.21gb</td>
    </tr>
    <tr>
        <td>8a</td>
        <td>vit_large_patch16_224(batch_size3)</td>
        <td>0.0220416884048366</td>
        <td>99.4444444444444</td>
        <td>1.28843541815876</td>
        <td>66.6666666666666</td>
        <td>0.453457333567914</td>
        <td>85.1851851851851</td>
        <td>0.78947368</td>
        <td>0.84210526</td>
        <td>0.9375</td>
        <td>0.83333333</td>
        <td>0.88888889</td>
        <td>0.83333333</td>
        <td>0.81081081</td>
        <td>0.86486486</td>
        <td>0.88235294</td>
        <td>18</td>
        <td>18</td>
        <td>18</td>
        <td>0.777777777777777</td>
        <td>1.21gb</td>
    </tr>
</table>

Among multiple models ```vit_base_patch8_224``` stood out in performance with a kappa score of **0.8888888888888888**

## Best model performance:
Model name: ```vit_base_patch8_224```
#### Test Performance: 
```LOSS : 0.22057782664861797  ACCURACY : 92.85714285714286
TEST PREC: [0.88888889 0.94444444 0.94444444] RECALL: [0.88888889 0.94444444 0.94444444] F1 SCORE: [0.88888889 0.94444444 0.94444444] SUPPORT: [18 18 18]
KAPPA:  0.8888888888888888
```
![ps2_kappa](https://user-images.githubusercontent.com/57902078/212657993-f84b8dc0-05cb-426c-a03d-0a0f92fed4ef.png)
![ps2_f1](https://user-images.githubusercontent.com/57902078/212657986-9f950fd7-19f2-491f-a33d-8f51e74e2502.png)
![ps2_loss](https://user-images.githubusercontent.com/57902078/212657995-921dcbab-6716-4714-b3af-921894ea2422.png)
![ps2_prec](https://user-images.githubusercontent.com/57902078/212657998-7172783f-a69e-41b4-8111-86be74f30bf9.png)
![ps2_recall](https://user-images.githubusercontent.com/57902078/212658003-4774b7f1-a037-4a13-981f-b295c3fdd9dc.png)
![ps2_acc](https://user-images.githubusercontent.com/57902078/212657955-0d8ceebc-50df-4912-87e7-b9a09c748003.png)


## Experimentation & Observation:

Main problem in the task that we came across is that the dataset was very insuffiecient. So we started  fine-tuning the given dataset on the standard pre-trained model such as Resnet, VGG16, Efficientnet-B7, and Vision Transformers (ViT). Due to very less data samples for each class we tried different augmentations but it didn't help in improving the models accuracy any further. After multiple runs, we found that ViT models outperformed all other models with/without augmentation and performed exceptionally well using the SGD optimizer in particular. Image augmentation, such as random rotation and flips, did not help in improving the model performance, and the model was able to generalize well without overfitting without any image augmentation.
All the models were trained using Kaggle GPU and partially locally.

## Other Approaches - Few Shot Learning:

We tried to use ![Matching Networks](https://arxiv.org/abs/1606.04080) to solve the issue of very less data samples. We started by using fintuned tiny ViT model as our feature extractor and minimized Tripple Loss on Euclidean Distance of the embedding feature vectors of each images with respect to each other. Then we trained a linear layer on top of this feature extracor by freezing it. But the results were bad even after applying different augmentations. One possible explanation is that the classess has overlapping image features and Tripple Loss on Euclidean Distances could have reduced generalization of the model.


