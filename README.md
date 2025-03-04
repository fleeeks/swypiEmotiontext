swypiEmotionText

swypiEmotionText is a simple Python library designed to analyze text and detect its underlying emotion—whether it's positive, negative, or neutral. It’s a quick and easy way to assess sentiment in social media comments, reviews, or general text.

Installation

To install swypiEmotionText, run the following command:

pip install https://github.com/fleeeks/swypiEmotiontext/releases/download/SwypiEmotiontext/swypiEmotionText.tar.gz

Alternatively, if you have the .tar.gz file downloaded locally, you can install it by specifying the file path:

pip install /path/to/swypiEmotionText.tar.gz

Usage

Once installed, using the library is straightforward. Simply pass a text string to the main function, and it will return:

emotion – Identifies the detected sentiment (positive, negative, or neutral).

score – A numerical value representing the strength of the detected emotion.


Key Features

Emotion Detection – Quickly determines whether text is positive, negative, or neutral.

Accuracy – Provides a numerical sentiment score to gauge emotional intensity.

Customization – Allows for adjustments to fine-tune emotion detection based on specific needs.


Error Handling

If invalid input or other issues occur, the library provides clear error messages to help troubleshoot the problem.

Example Scenarios

Positive Emotion: "I am so happy today!" → Detected as positive.

Negative Emotion: "I feel terrible." → Detected as negative.

Neutral Emotion: "The weather is fine." → Detected as neutral.



---
