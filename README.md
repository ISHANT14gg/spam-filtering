# Spam Classifier

## Overview

The Spam Classifier is a Python function designed to determine the likelihood that a given message is spam. This function uses probabilistic methods to classify messages based on the presence of specific words and their frequencies in spam and non-spam (ham) datasets.

## Features

- **Message Classification**: Determines if a message is spam based on word frequencies.
- **Adjustable Parameters**: Allows customization of background strength and prior probability.
- **Result Format**: Returns the spam probability as a percentage or a boolean value.

## Function: `spam`

### Description

The `spam` function classifies a message as spam or not using probabilistic models. It leverages word frequencies from spam and non-spam messages to compute the probability of the message being spam.

### Parameters

- `message` (str): The message to be classified. Must be a non-empty string.
- `s` (float, optional): The strength of background information about incoming spam. Default is `1`.
- `p` (float, optional): The prior probability of any incoming message being spam. Default is `0.5`.
- `percentage` (bool, optional): If `True`, returns the result as a percentage. If `False`, returns a boolean value. Default is `True`.

### Returns

- If `percentage` is `True`, prints the spam probability as a percentage.
- If `percentage` is `False`, returns `True` if the message is classified as spam, and `False` otherwise.
pip install numpy
In this README, I've added a "Key Results" section to highlight the 91\% accuracy achieved by your model.

Feel free to copy and paste this into your `README.md` file on GitHub. If you need further adjustments, just let me know!
