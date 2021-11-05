# Elephants
#### The population of African elephants (Loxodonta africana) has plummeted over the last century due to poaching, retaliatory killing for crop raiding and habitat fragmentation. 
### [How can we count elephants?](https://www.cnet.com/news/scientists-count-elephants-from-space-with-satellites-and-computer-smarts/#ftag=COS-05-10aaa0j)
- Algorithm developed by Dr Olga Isupova, a computer scientist at the University of Bath.
- Using satellite imagery from [Maxar satellites](https://www.cnet.com/news/scientists-count-elephants-from-space-with-satellites-and-computer-smarts/#ftag=COS-05-10aaa0j) Worldview 3 and 4 
- "For the first time, scientists have successfully used satellite cameras coupled with deep learning to count animals in complex geographical landscapes," said the University of Bath
- Deep learning was done using the [Tensor Flow API](v) and detection has accuracy comparable to human abilities.
- This offers an effective alternative to counting elephants from aircraft which is expensive and can only cover a limited amount of ground.
- As it sweeps across the land, a satellite can collect over 5,000 km² of imagery in a matter of minutes, eliminating the risk of double counting and allowing repeat surveys over short intervals.
 - The data was then processed by the deep learning model which could do it in a matter of hours rather than months.
 - The model was developed by feeding a customised training dataset of more than 1000 elephants in South Africa into a [Convolutional Neural Network(CNN)](https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53v).
 - The results (known as the [F2 score](https://machinelearningmastery.com/fbeta-measure-for-machine-learning/)) of the CNN models was 0.78 in heterogeneous areas and 0.73 in homogenous areas, compared with, an averaged human detection capability F2 score of 0.77 in heterogeneous areas and 0.80 in homogenous areas.

![image.png](https://earimediaprodweb.azurewebsites.net/Api/v1/Multimedia/f3e76ff4-b3ce-47a3-bab0-7baf34154a0a/Rendition/low-res/Content/Public)
- Similar projects have been undergone before. For example NASA used satellite technology to find a [secret penguin colony](https://www.cnet.com/news/nasa-satellite-reveals-penguin-supercolony-antarctica-adelie/). However this has never been done in a heterogeneous landscape like the African savanna.
 - There are an estimated 415,000 African elephants left in the wild and they are listed as "vulnerable" on the [IUCN Red List of Threatened Species](https://www.iucnredlist.org/species/12392/3339343).
 - This means its vital to keep track of their numbers and locations.
 - The teams are currently working on software to track the smaller animals but elephants are an excellent start.
###### Paper: [c](https://zslpublications.onlinelibrary.wiley.com/doi/full/10.1002/rse2.195)


### [How can we prevent poaching?](https://www.seas.harvard.edu/news/2020/02/coding-uncertainty-increases-security)

- Currently drones are flying over wildlife parks in South Africa, equipped with thermal infrared cameras and smart automatic detection systems that can identify potential poachers and alert ranger.
- However rangers are not always available since parks are huge so a new [paper](https://www.semanticscholar.org/paper/To-Signal-or-Not-To-Signal%3A-Exploiting-Uncertain-in-Bondi-Oh/6c13529720f1a3fc3969b7f1531c1ce6e8d9d22d?p2df) has been looking at how they can prevent poaching without needing rangers.
- Computer Scientists at [Harvard John A. Paulson School of Engineering and Applied Sciences](https://www.seas.harvard.edu/) are using the uncertainty in the drones readings to dissuade poachers.
- "We’ve turned our uncertainties into our advantage." - ELIZABETH BONDI, SEAS GRADUATE STUDENT
- In the algorithm, called GUARDSS, if a drone see's a poacher it will signal if there is a nearby ranger, if not then the algorithm will calculate if it should signal or not based on a calculation. It may even signal if it see's nothing.
- This algorithm gives them an advantage over the poachers since they don't know if they've been seen.
