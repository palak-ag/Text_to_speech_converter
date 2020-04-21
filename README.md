# Text_to_speech_converter

It is an application which is used to convert any text into speech in any desirable language. It is made for the beneficial of the people who can't see and are much intrested in reading. Even the persons who wants to read or listen the book in different languages can avail the facility. 

We used cv2 to take the picture and then pytesseract to get the image in the PC to change the language using "SentimentIntensityAnalyzer" where Sentiment Analysis is the process of ‘computationally’ determining whether a piece of writing is positive, negative or neutral. It’s also known as opinion mining, deriving the opinion or attitude of a speaker.

VADER Sentiment Analysis :

VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media. VADER uses a combination of A sentiment lexicon is a list of lexical features (e.g., words) which are generally labeled according to their semantic orientation as either positive or negative. VADER not only tells about the Positivity and Negativity score but also tells us about how positive or negative a sentiment is.

We even used Textblob to process the textual data. 

TextBlob is a Python (2 and 3) library for processing textual data. It provides a simple API for diving into common natural language processing (NLP) tasks such as part-of-speech tagging, noun phrase extraction, sentiment analysis, classification, translation, and more.

And then we used gtts to convert text to speech in the desired language of the user. 

gTTS
gTTS (Google Text-to-Speech), a Python library and CLI tool to interface with Google Translate's text-to-speech API. Write spoken mp3 data to a file, a file-like object (bytestring) for further audio manipulation, or stdout. Or simply pre-generate Google Translate TTS request URLs to feed to an external program. http://gtts.readthedocs.org/
