# multi-label-dataset

Given the multi-label data set $S=\{(\boldsymbol{x_i},Y_i)|1\leq i\leq m\}$,we use$|S|,dim(S),CL(S)$ to denote the number of examples, features, class labels, and $F(S)$ to denote the feature type.Furthermore, several other multi-label properties are denoted as:

$LCard(S)=\frac{1}{|S|}\sum_{i=1}^{|S|}|Y_i|$: Label cardinality counts the  average number of relevant labels per example;

$LDen(S)=\frac{LCard(S)}{CL(S)}$: Label density normalizes label cardinality by the number of class labels;

$DL(S)=|\{Y|\exists \boldsymbol{x}:(\boldsymbol{x},Y)\in S\}|$: Distinct label sets counts the number of distinct label vectors existing in $S$;

$PDL(S)=\frac{1}{|S|}\cdot DL(S)$: Proportion of distinct label sets normalizes distinct label sets by the number of examples.

| Data set      | $|S|$ | $dim(S)$ | $CL(S)$ | $LCard(S)$ | $LDen(S)$ | $DL(S)$ | $PDL(S)$ | Domain  |
| :------------ | :---: | :------: | :-----: | :--------: | :-------: | :-----: | :------: | :-----: |
| CAL500        |  502  |    68    |   174   |   26.044   |   0.150   |   502   |   1.00   |  music  |
| languagelog   | 1460  |   1004   |   75    |   1.180    |   0.016   |   286   |  0.196   |  text   |
| enron         | 1702  |   1001   |   53    |   3.378    |   0.064   |   753   |  0.442   |  text   |
| image         | 2000  |   294    |    5    |   1.236    |   0.247   |   20    |  0.010   |  image  |
| scene         | 2407  |   294    |    6    |   1.074    |   0.179   |   15    |  0.006   |  image  |
| yeast         | 2417  |   103    |   14    |   4.237    |   0.303   |   198   |  0.082   | biology |
| slashdot      | 3782  |   1079   |   22    |   1.177    |   0.054   |   148   |  0.039   |  text   |
| corel5k       | 5000  |   499    |   374   |   3.522    |   0.009   |  3175   |  0.635   |  image  |
| rcv1(subset1) | 6000  |   944    |   101   |    2.88    |   0.029   |  1028   |  0.171   |  text   |
| rcv1(subset2) | 6000  |   944    |   101   |   2.634    |   0.026   |   954   |  0.159   |  text   |
| bibtex        | 7395  |   1836   |   159   |   2.402    |   0.015   |  2856   |  0.386   |  text   |
| corel16k-s1   | 13766 |   500    |   153   |   2.859    |   0.019   |  4803   |  0.349   |  image  |
| eurlex-dc     | 19348 |   5000   |   412   |   1.292    |   0.003   |  1615   |  0.084   |  text   |
| tmc2007       | 28596 |   981    |   22    |   2.158    |   0.098   |  1341   |  0.047   |  text   |
| mediamill     | 43907 |   120    |   101   |   4.376    |   0.043   |  6555   |  0.149   |  video  |

