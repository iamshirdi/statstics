# statstics cheat sheet notes

## LINEAR RELATIONSHIP
- When y =mx+b the large constant is added to small . it dominates small which will result in price per unit large compared to when constant is large and y is also large . y dominates so price per unit is small compared to when y is small
- Its like **fixed fee - constant-b** even wether you buy small or large. While you profit per sqm if you buy high cost house compared to small cost with constant fee
- The higher price (y) we go the constant price becomes negligible for a given x (sqm)
- Scatter plot (data points are not joined together usually) is not good for noisy data unlike barchart
- Noise can be due to numerous reasons like old house, remodelling, view,area which are not included. Which resulted in non linear relationship between size and cost (cost should increase with size)
<img src = static/noise.PNG>

- BAR Chart pool together and make half in y axis. It helps in large data pool find wether increasing or decreasing as shown in image
<img src = static/bar.PNG>

- Histograms are kind of barchat (2D) which focuses on 1D data. usually frequency-count on y axis. Example: Majority of salary in one bin and minority in another bin. Similarly age distribution
- Pie chart is used for specifically relative data (percentage)
- Individually if less number it may cause bias when compared in total. Example Major A,B and Gender M,F with low acceptance, high acceptance :Ambigious
- In Linear plot . Line passing through Origin will indicate that points on line results in X=Y and above line , below line to easily know wether one value is greater than other. L(Y), B(X) where above line indicates Length is greater than breadth of that square,person etc

## Probability
- Probability (Causes --> Data) is opposite of statstics (Data --> Causes).
- Probability of composite event is P.P.P (Independence - outcome of second or third event does not depend on first)
 <img src = static/truth-table.PNG>

- Conditional Probablity - the four combined probabilities listed are 0.09, 0.01, 0.18, and 0.72. Total probabiltiy of positive test result is 0.27
<img src = static/conditional-probability.PNG>

- Flipping fair and baised coin twice . order given H then T probaility
<img src = static/flip-twice-coin.PNG>

- Bayes Rule: sensitiveity (positivity : P(pos/c)) and specificity: P(neg/>c)
- prior probability (0.01 percent cancer population) * test evidence (test) = posterior probablity P(c/pos) : P(c/pos) = P(c) * p(pos/c) divide by normalizer P(c,Pos)+p(>c,Pos) to make it 1 toatl probaibliy 
- Before test P(c) = 0.01 after test it went down by a factor p(c/neg) = 0.0011
<img src = static/bayes-rule.PNG>

- how a test helps(rain looking) to increase the probability (to check if I am at a home or not)
<img src = static/bayes-example.PNG>