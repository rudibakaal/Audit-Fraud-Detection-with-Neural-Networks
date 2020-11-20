# Audit-Fraud-Detection-with-Neural-Networks

## Motivation
Neural network trained on data garnered from the Auditor Office of India to build a predictor for classifying suspicious firms.

The goal of the research is to help the auditors by building a classification model that can predict the fraudulent firm on the basis the present and historical risk factors[1].

## Neural Network Topology and Results Summary
The binary-crossentropy loss function was leveraged along with the rmsprop optimizer for this classification problem.

![model](https://user-images.githubusercontent.com/48378196/96961401-4be81500-1550-11eb-9cd2-4e0f682c3b56.png)

By the 55th epoch, binary and validation accuracy both reach 98% accuracy in correctly classifying fraudulent firms. 

![audit](https://user-images.githubusercontent.com/48378196/99758466-ddde4000-2b45-11eb-8502-2efb1333b838.png)

## License
[MIT](https://choosealicense.com/licenses/mit/) 

## References
[1] Hooda, Nishtha, Seema Bawa, and Prashant Singh Rana. 'Fraudulent Firm Classification: A Case Study of an External Audit.' Applied Artificial Intelligence 32.1 (2018): 48-64.
