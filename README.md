# cs5890dataScience
Stock analysis using R

First off you want to choose a stock or mutual fund that has a positive book value per share, and one with a safe beta. 
You can find these values on yahoo finance, under key statistics. And of course one with a positive cash flow, and one with not a reverse stock split.

Buy and sell: If red line goes up and crosses, then you sell. You buy when the green line shoots up and crosses the red line. 

to create these lines we use a formula that can be adjusted, your choice of how many periods you want to use.

green line formula: ((number of periods - number of periods since highest high) / number of periods)*100

red line formula: ((number of periods - number of periods since lowest low) / number of periods)*100

