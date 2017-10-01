# Tripadvisor Naive Bayes 

A Naive-Bayes-Classifier trained with subreviews from TripAdvisor to calculate a overall rating based on given subratings.

## Install

Before using the Application dependencies have to be installed.
These can be installed with the following command over pip.

```
$ pip install -r requirements.txt
```

## Usage

The Server can be started running the `__init__.py` file.

```
$ python __init__.py
```

The web interface can be accessed over the ``index.html`` file in the ``web_interface`` folder.

## Force Training

The training data can be pulled from ``http://times.cs.uiuc.edu/~wang296/Data/``, have to be in json format and need to be in a ``json`` directory in the project root.

![folder structure](folder-structure.png)

Now you can start the program with forced training by using the `--ft` flag like this:

```
$ python __init__.py --ft
```
## Project Members
- Matthias Herrmann (Naive Bayes Implementierung mit nltk)
- Sarah Kocher (Weboberfläche)
- Benedikt Straser (RESTful Server)
## License

[MIT License](LICENSE)

Attribution for the ratings data from tripadvisor:

Hongning Wang, Yue Lu and ChengXiang Zhai. Latent Aspect Rating Analysis without Aspect Keyword Supervision. The 17th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD'2011), P618-626, 2011.
Hongning Wang, Yue Lu and Chengxiang Zhai. Latent Aspect Rating Analysis on Review Text Data: A Rating Regression Approach. The 16th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD'2010), p783-792, 2010.
