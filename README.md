#2021.3.1-3.30 : We discussed the functional requirements in this project and desided to use semi-supervised random forests. Then I started to working on my proposal. During this period, I also read some papers that wrote in the references.

#2021.3.30: This project initially updated to Github

#2021.3.31: We discussed the implementing processes of decision-trees and made the goal of next week which is to read the paper 'Semi-supervised random forest' and ,if time is enough, implement my own implemented decision tree.

#2021.4.22: After Richard and Charlotte took two-week vacation, we discussed the process of semi-supervised random forest. During this progress, the entropy will also be used as a measured score of the possobility that which classification does one data belongs to . 

#2021.5.6: Since last week I had several dealines and a exam to take, we didn't have a meeting. In this week, dataset from hospital is finally got but still need to be read by computer. We discussed the detail of algrithom in random forest and decide to complish an important and tricky equation in the algrithm in next week. 
[image](https://user-images.githubusercontent.com/73624319/117657314-53d87100-b191-11eb-8241-c0ef35e24869.png)

#2021.5.12: Last week we decided to finish the equation, but there is a problem with g(x) part. We found it is impossible to use 
l(g(x))=log(p_i(x)-1/K) 
as the loss function, where the p_i(x) is the possibility of node x voted for the ith class and K is the number of the classes. Because, the result of g(x) could be negitive sometimes and it have no log value. Therefore, we decide to use l(x) = log(p_i(x)) instead to understand the logic first and continus searching for the information of g(x). And next week, I will finish this equation and add it into the random forests that I've wroten.
