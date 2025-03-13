Language: python

There are multiple options for linting in python for examples Pylint and Flake8. Both follow the PEP8 standard for python coding. 
There exists a testing module called "unittest", which allows making test cases for specific parts of the code. The test cases can be run individually or one by one. 
In python building would generally mean to make sure all dependencies are avaliable. This can be done with a setup script, which downloads and install the dependencies.

Alternative CI setup methods include GitLab CI and CircleCI. GitLab is a remote git repository similar to GitHub and also offers CI workflows whicle CircleCI only offers CI workflows. 

Both GitLab and CircleCI are avaliable for self hosting, but it is much simpler to use their cloud based environments. Things following can affect the decision of whether to self host:

### cost
- If the cost of the cloud service is lower than self hosting an instance, then with the added simplicity of the cloud instance it may be a better optiion.
### speed
- The speed of CI workflow may affect the development time.
### avaliability.
- If the self hosted instance can't be reliably hosted with high avaliability it may be a better option to use the cloud instance. On the other hand, if the cloud hosted instance goes down, it is out of the hands of the dev team and a self hosted instance may be better.