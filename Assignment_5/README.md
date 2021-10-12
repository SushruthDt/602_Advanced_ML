# Concrete strength prediction


### Data Set Abstract :
Concrete is the most important material in civil engineering. The concrete compressive strength is a highly nonlinear function of age and ingredients. The concrete compressive strength is a highly nonlinear function of age and ingredients. These ingredients include cement, blast furnace slag, fly ash,water, uperplasticizer, coarse aggregate, and fine aggregate

### Source - UCI
Original Owner and Donor Prof. I-Cheng Yeh Department of Information Management Chung-Hua University, Hsin Chu, Taiwan 30067, R.O.C. e-mail:icyeh '@' chu.edu.tw TEL:886-3-5186511

### Data Set Information
● Number of instances : 1030
● Number of Attributes: 9
● Attribute breakdown 8 quantitative input variables, and 1 quantitative output variable
● Missing Attribute Values: None'

### Data Dictionary
Feature Description and data types -
● Cement: a substance used for construction that hardens to other materials to bind them together, (measured in kg in a m3 mixture).
● Slag: Mixture of metal oxides and silicon dioxide, (measured in kg in a m3 mixture).
● Flyash: coal combustion product that is composed of the particulates that are driven out of coal-fired boilers together with the flue gases, (measured in kg in a m3 mixture).
● Water: It is used to form a thick paste, (measured in kg in a m3 mixture).
● SuperPlasticizer: used in making high-strength concrete, (measured in kg in a m3 mixture).
● CoaseSeaggregate: prices of rocks obtain from ground deposits, (measured in kg in a m3 mixture).
● Fineaggregate: the size of aggregate small than 4.75mm, (measured in kg in a m3 mixture).
● Age: Rate of gain of strength is faster to start with and the rate gets reduced with age,day (1~365).
● CsMPa: Measurement unit of concrete strength,Concrete compressive strength measured in MPa [OUTPUT VARIABLE] .

### Analysis Done
To understand which features are important when it comes to increasing the strength of the cement. In addition, algorithms must be used to predict strength and select the best one among them.

### Conclusion
I discovered through EDA that cement, age, and superplasticizer all have a positive impact on overall strength. Water has been found to have a negative impact on concrete, but it is frequently present in older concrete due to curing processes.
Using linear regression models, it was discovered that blast furnace slag is far more important than previously thought, and that superplasticizer is far less important. These are not intuitive insights, but they could be profound and useful in a business setting.
All of our linear regression models scored similarly in the scoring metrics and would be suitable for further prediction and testing in a production environment.
To improve the prediction score, perhaps decision trees and ensemble methods could be used.


