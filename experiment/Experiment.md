# Introduction

The question ids of selected Winograd questions are shown in Selected_question.txt

The prediction results of PP and SP-10K are shown in PP_prediction.txt and SP-10K_prediction.txt respectively.

To see the ground truth about using second-order selectional preference for winograd schema challenge, we also annotate all the related 2-hop SP pairs.
The prediction result is in All-annotated_prediction.txt


# Result

| SP knowledge resource | # correct     | # wrong  | # No answer| Absolute Acc. | Overall Acc.|
| :-------------:       |:-------------:| :-----:| :-----:| :-----:| :-----:|
| PP                    | 36 | 19 | 17 | 65.5% | 61.8% |
| SP-10K                | 13 |  0 | 59 | 100%  | 59.0% |
| All-annotated         | 45 |  9 | 18 | 83.3% | 75.0% |