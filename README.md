1 - Introduction:
The goal is to implement and practice some basic text processing techniques in NLP for the
Urdu language. The Urdu language is written in a different style as compared to English, making segmentation
a challenging task. There can be several reasons but Space Insertion Problem and Space Omission Problems
are the major ones. This task is to perform Urdu sentence segmentation. This task
is designed to be completed from scratch. It uses basic libraries and you can improve existing libraries like urduhack (https : //urduhack.com/), but the functions available in
these libraries do not perform up to their potential.

2 - Background:
Sentence segmentation is the process of determining longer processing units consisting of more than one word.
This task involves identifying sentence boundaries between words in different sentences. Here is an example of
text combination of two sentences:
بے چاری عوام چونکہ ہمیشہ سے دھوکہ کھانے کی عادی رہی ہے اس لئے ‘‘تبدیلی سرکار’’ کی چکنی چپڑی باتوں میں آگئی اور اپنے بہتر مستقبل
کے لئے نئی حکومت کو اقتدار کے ایوانوں تک پہنچا دیا
You have to develop a technique that will perform segmentation of sentences and remove extra white spaces in
sentences for example by passing the above statement, your model should generate output:
بے چاری عوام چونکہ ہمیشہ سے دھوکہ کھانے کی عادی رہی ہے۔ اس لئے ”تبدیلی سرکار“ کی چکنی چپڑی باتوں میں آگئی اور اپنے بہتر
مستقبل کے لئے نئی حکومت کو اقتدار کے ایوانوں تک پہنچا دیا۔

3 -  Challenges in Implementing a Model:
 Several decisions were made in implementing the sentence segmentation technique and its evaluation:
A. How can this detect patterns from the text?
B. Will this identify the end-words of a sentence in Urdu?
Note: Simply counting the number of segments may not be enough!
