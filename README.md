# Comparison of GMM-based and CNN-based speaker identification using two public datasets

The analysis compares the performance of two different approaches for speaker identification:
CNN and GMM, which are evaluated on two datasets and their respective subsets, with short and
long utterances. AudioMNIST is referred as AM and consists of short utterances from 60 
speakers, with 100 audios from each speaker, where as Librispeech is referred as LS and 
consists of long utterances from 81 speakers, with 100 audios from each speaker for the 
experiments. AM and AM-Sub contain 70 and 30 audios per speaker for training, respectively. 
AM and AM-Sub contain the same 20 audios per speaker for testing, while ignoring the same 10 
audios per speaker for validation as GMM does not require it. LS and LS-Sub contain 70 and 30 
audios per speaker for training, respectively. LS and LS-Sub contain the same 10 audios per 
speaker for validation and 20 audios per speaker for testing. 

The table below shows the number of files per peaker used in Training, Validation and Testing:
|  Method  |  AM  | AM-Sub |  LS  | LS-Sub |
|   ---    |  --- |   ---  |  --- |  ---   |
| Training |  70  |   30   |  70  |   30   |
|Validation|  10  |   10   |  10  |   10   |
| Testing  |  20  |   20   |  20  |   20   |

And, the table below shows the layout of the eight experiments performed:
|  Method  |  AM  | AM-Sub |  LS  | LS-Sub |
|   ---    |  --- |   ---  |  --- |  ---   |
|   GMM    | EXP 1|  EXP 2 | EXP 3| EXP 4  |
|   CNN    | EXP 5|  EXP 6 | EXP 7| EXP 8  |



