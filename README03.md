# Terry Stops
Decision Trees and Random Forest Classifiers

## Objectives
Determine the most appropriate classifier for the dataset
Find out whether the differences in the race of the subject and the officer had an effect on the likelihood of arrest
Find out whether the type of the weapon, identification and gender of officers played a role in the outcome of a Terry Stop

## What classifier works best for the dataset?
Both decision trees and random forest had acceptable precision, recall, accuracy and F1 scores. Random Forest seemed to have a more appropriate feature importance. For example, it showed both the precense and absense of a weapon, as well as the subject's precense of ID and officers gender to be important features.

![Imgur](https://i.imgur.com/thqB1Eb.png)

![Imgur](https://i.imgur.com/vx4DCVM.png)

## Is the likelihood of an arrest higher when the officer and the subject are the same race?

![Imgur](https://i.imgur.com/9T4uUbG.png)
![Imgur](https://i.imgur.com/54LOJjd.png)

There didn't seem to be any immediately noticeable differences between the two situations. A closer look is necessary to say with more certainty. The differences in the likelihood of other outcomes of a Terry Stop could be present.

## Is the precense of the weapon more likely to lead to an arrest?

![Imgur](https://i.imgur.com/jxJNeXg.png)

Yes. When we divided the dataset according to the presence of a weapon, the proprtion of arrests resulting from a Terry Stop was shown to be higher. The absense of ID in subjects also increased the likelhood of arrest.

### Recomendation
Be more careful and thorough in determening whether the possession of the weapon is lawfull to avoid unnecessary arrests. Use other identifying techniques in case the ID is missing, e.g. checking the finger prints, SSN, or other information to reduce the unnecessary arrests resulting from a lack of ID.

# Conclusion
Random forest happens to be the best classifier due to feature importance, decision tree also works well. The presence of a weapon and a lack of ID increase the chances of arrest, however the differences between officer and subject race don't seem to have a significant effect. Overall, alternative methods of identyfication and a thorough check of the lawfullness of the weapon are needed to avoid unneccessary arrests.



