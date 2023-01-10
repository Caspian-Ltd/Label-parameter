NOTE-  this project in no longer live or supported in any way. Please do not attempt to contact the developer.
thanks.


### Finding the Ground-Truth from Multiple Labellers: Why Parameters of the Task Matter

Contained within this repo are the results from the experiments in the paper 'Finding the Ground-Truth from Multiple Labellers: Why Parameters of the Task Matter'. The notebook can run a single experiment instance, with all parameters easy to change.

Please note, you will need to use the Dawid & Skene method in this library for expectation maximisation. This EM code has been taken from https://github.com/dallascard/dawid_skene. The only changes that have been made to the code from Dallas Card's original are ones that make it work in Python 3 (the original was written for Python 2).

The more you increase the the parameters, the longer it will take to complete (particularly for sample size). A lot of this computational time is taken up by CrowdTruth (or at least the version used in this repo) due performing a lot of string operations. You may be able to find other ways around this to improve it!
