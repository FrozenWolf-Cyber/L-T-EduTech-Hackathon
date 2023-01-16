# L-T-EduTech-Hackathon
Solutions of L&amp;T EduTech Hackathon by our team  - Bharatfly_Coders 

**Each** folder contains a ![README.md](https://github.com/FrozenWolf-Cyber/L-T-EduTech-Hackathon/tree/main/PS3#readme) folder explaining the results, metrics, training and observations in detailed.

Throughout all task general observation is that the Vision transformers (ViT) performed very well compared to classical models such as Resnet, VGG16, EfficientNet-Bx.

## Results:

## ![PS1](https://github.com/FrozenWolf-Cyber/L-T-EduTech-Hackathon/tree/main/PS1#readme):
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

#### Best model performance:
Model name: ```vit_tiny_patch16_224```
```LOSS : 0.008621435415429564  ACCURACY : 100.0
TEST PREC: [1. 1.] RECALL: [1. 1.] F1 SCORE: [1. 1.] SUPPORT: [100 100]
```

## ![PS2](https://github.com/FrozenWolf-Cyber/L-T-EduTech-Hackathon/tree/main/PS2#readme):


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

#### Best model performance:
Model name: ```vit_base_patch8_224```
```LOSS : 0.22057782664861797  ACCURACY : 92.85714285714286
TEST PREC: [0.88888889 0.94444444 0.94444444] RECALL: [0.88888889 0.94444444 0.94444444] F1 SCORE: [0.88888889 0.94444444 0.94444444] SUPPORT: [18 18 18]
KAPPA:  0.8888888888888888
```

## ![PS3](https://github.com/FrozenWolf-Cyber/L-T-EduTech-Hackathon/tree/main/PS3#readme):


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
#### Best model performance:
Model name: ```vit_base_patch8_224```

``` VALIDATION LOSS for EPOCH 30 : 0.029897840079502202
  VALIDATION PREC : [0.95454545 1.         1.         1.         0.93478261]
  RECALL : [0.93333333 1.         1.         1.         0.95555556]
  F1 : [0.94382022 1.         1.         1.         0.94505495]  
  ACC : 98.75  KAPPA : 0.97
```
