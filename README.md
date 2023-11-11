# I-310D-Data-Bias

This project's objective is to investigate the idea of bias by using an existing natural language processing tool, namely the Perspective API made available by Google Jigsaw. For this project, I created my own queries, analyzed an existing dataset of comments and their scores, and use the Perspective API client to assess the toxicity of each comment.

## Hypothesis:
My hypothesis is, when analyzing toxic comments about rich individuals, the Perspective API is more likely to make mistakes than when studying toxic comments about poor people. I have collected ten comments about rich people (five toxic and five non-toxic), ten comments about poor people (five toxic and five non-toxic), and I have tested them using the Perspective API client to see whether it accurately classifies them as toxic or non-toxic.

I have uploaded two files for this project which are the I 310D: Data Bias.csv which has the raw comments and the I 310D: Data Bias.ipynb which contains the code and the processing.

## Conclusion: 

Based on the results I have gotten, I have reached the conclusion that my hypothesis is inaccurate. The non-toxic comments for both rich people and poor people were both predicted to be 100% accurate. But when this was transitioned to toxic comments the accuracy for both rich and poor people fell to 60% accuracy of predicting it correctly. This reduction in accuracy can be attributed to the Perspective API's inability to classify toxic comments properly. It needs to be stricter with the classication of toxic comments. But this cannot be attributed to the fact that it is related to rich or poor people because the fall from non-toxic to toxic comments is the same (100% to 60%). This shows some of the limitations of the Perspective API but discriminating between rich and poor people is not one of these vulnerabilities.
