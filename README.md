# Watson Developer Cloud APIs - Performance Evaluation Utilities
This repository contains a set of Jupyter notebooks that help you in evaluating the performance of your trained Watson Developer Cloud services. Specifically, it includes notebooks for [Natural Language Classifier](https://www.ibm.com/watson/developercloud/nl-classifier.html), [Watson Conversation Service](https://www.ibm.com/watson/developercloud/conversation.html), [Watson Discovery Service]
(https://www.ibm.com/watson/developercloud/discovery.html) and [Watson Visual Recognition]
(https://www.ibm.com/watson/developercloud/visual-recognition.html) service. 

I will add notebooks for other services as they become available.

## Prerequisites
To use these notebooks, you need the following:
* A Unix-based OS (or Cygwin)
* [virtualenv](https://virtualenv.pypa.io/en/stable/installation/)
* [Git](https://git-scm.com/downloads)
* [python 2](https://www.python.org/downloads/) or [python 3](https://www.python.org/downloads/)
* [Anaconda](https://www.continuum.io/downloads) - Installing this package also installs the Jupyter notebook package, which includes iPython (now referred to as jupyter)
* A [Bluemix](https://bluemix.net) account
* An instance of the Watson service of interest

If you are using a Linux system, the git, anaconda, python, and node.js packages may be installable through your system's package manager.


## Installing dependencies for the notebooks
* **pip install watson-developer-cloud**
* **pip install pandas-ml**

## Running the Notebooks
* **git clone https://github.com/lkrishnamurthy/wdcutils.git**
* Open **example_parms.json** in a text editor and update the parameters:
  * NLC credentials(url, username, password)
  * classifier id of trained classifier
  * input test csv file 
  * results csv file to write output results to including confidence of classification results
  * confusion matrix csv file to write the confusion matrix with labels
* **jupyter notebook** ==> this launches the notebook in a browser.
* Navigate to **notebooks** directory
* **Click NLCPerformanceEval.ipynb**
==> This launches the notebook for measuring performance of your trained classifier of Natural Language Classifier instance.
* Point to example_parms.json file in your notebook.
* Execute the various steps of the notebook by providing the required parameters.

# License

  This sample code is licensed under Apache 2.0.
  Full license text is available in [LICENSE](LICENSE).

