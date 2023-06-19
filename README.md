# ML_from_scratch
This Repository contains the implementation of machine learning models from scratch.

<ul>
    <li>Decision Trees</li>
        <ul>
            <li>for Classification</li>
                <ul>
                    <li>ID3 algorithm</li>
                        <ul>
                            <li>Uses Entropy gain as criteria to find the best-split node</li>
                            <li>No overfitting/underfitting is applied</li>
                        </ul>
                </ul>
            <li>for Regression</li>
                <ul>
                    <li>C4.5 Algorithm</li>
                        <ul>
                            <li>uses standard error to find the best-split node</li>
                            <li> Overfitting has been taken care of with the minimum coefficient of variance limit</li>
                            <li>Data Predicted on covid cases in India with an RMSE of `0.0649645496655877`</li>
                        </ul>
                    <li>CART Algorithm</li>
                        <ul>
                            <li>uses RMSE as criteria to determine the best-split node</li>
                            <li>Overfitting has been taken care of with the maximum depth of the tree</li>
                            <li>Data Predicted on covid cases in India with an RMSE of `0.2074162305521719`</li>
                        </ul>
                  Algorithms are designed in such a way as to predict results based on multiple variables, and single variables also
        Linear Regression
                </ul>
        </ul>
    <li>Linear Regression</li>
    ** Applied to linear functions, trigonometric functions (a*sin(x)+b*cos(x)), exponential functions(a*exp(bx)*cos(cx) + d*exp(ex)*sin(fx))
    ** For training data, random error is added to test the validity of the Regression
        <ul>
            <li>Univariate Linear Regression</li>
                <ul>
                    <li>Optimization algorithm - Gradient Descent</li>
                </ul>
             <li>Polynimial Linear Regression</li>
                <ul>
                    <li>Optimization algorithm - Gradient Descent</li>
                    <li>Can give a reduced polynomial of user-defined degree</li>
                    <li>Overfitting is shown with an increasing degree for model</li>
                    <li>Algorithm to find the best degree of Regression equation</li>
                </ul>
        </ul>
    
</ul>
      
       
        
 
