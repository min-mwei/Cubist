# Cubist

A Python package for fitting Quinlan's Cubist regression model

Inspired by the R wrapper for cubist https://github.com/topepo/Cubist

## architecture
Taking inspiration from the R wrapper this is what needs to be done
1. Get cubist compiled on own machine so we have binary available
1. Understand the inputs the binary require. The training dataset needs to
Conform to an expected format. May need to write python code that converts
Pandas dataframe to this.
1. Write python code that forks off cubist process with correct arguments
And files
1. Write interpreter that translates cubists model definition to executable
Python code.
1. Write pypi package that bundles all this
1. Enhance package to compile cubist on users machine
1. Make python translation performant by using scipy or numpy
1. Adapt api to conform to scikit learn
1. Submit package to scikit learn 

links:
https://www.linkedin.com/pulse/machine-learning-example-r-using-cubist-kirk-mettler
http://rulequest.com/cubist-info.html

Help welcome
