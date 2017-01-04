[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Natural Language Processing - Sentiment Analysis

Presentation Slides - http://slides.com/karalanglois/sentiment-analysis

## What is NLP?

NLP is a field of study that focuses on the interaction between human language and computers.  It branches across the fields of Computer Science, Artificial Intelligence and Computational Linguistics.

"NLP is a way for computers to analyze, understand, and derive meaning from human language in a smart and useful way." <br>http://blog.algorithmia.com/introduction-natural-language-processing-nlp/

## History

NLP primarily started in the 1950s.  It started off with fairly basic examples using hard-coded rules, and it wasn't until the late 1980s that the concept of machine learning was introduced.  As machine learning has advanced and computational power has increased, so have the capabilities of NLP.

-   1950s
  - [Turing Test](https://en.wikipedia.org/wiki/Turing_test) - A test developed by Alan Turing to measure the ability of a machine to exhibit intelligent behavior indistinguishable from a human.
  - [Georgetown Experiment](https://en.wikipedia.org/wiki/Georgetown%E2%80%93IBM_experiment) - A machine translation experiment to automatically translate 60+ sentences from Russian into English.
-   1960s
  - [SHRDLU](https://en.wikipedia.org/wiki/SHRDLU) - A program that parsed user instructions and moved various objects around it's "blocks world" per those instructions.
  - [ELIZA](https://en.wikipedia.org/wiki/ELIZA) - A program that simulated conversation using directives provided by 'scripts.'  It had no understanding of context or true intelligence, but many early users felt as though it did.
-   1970s
  - "conceptual ontologies" - converted real-world data information into data that a computer could understand
  - improved chatterbots
- 1980s - present
  - migration from hard-coded rules to machine learning (what modern NLP algorithms are based on)

## Examples of NLP Tasks

NLP encompasses a lot of different topics and tasks, but some examples are:

-   Machine translation - Translating text from one language to another.
-   Named entity recognition - Determine which items in the provided text map to proper names and the type of each (ex. person, location, etc.).
-   Relationship extraction - Determine how named entities are related to one another.
-   Part-of-speech tagging - Determine the parts of speech for each word in a given sentence.  Can be challenging since some words can serve as multiple parts of speech.
- Topic segmentation/recognition - Separate a block of text into chunks related to different topics and identify those topics.
- Speech processing - Includes both speech recognition and text-to-speech.
- Sentiment Analysis -  Determine the emotional tone behind the provided text.

## Sentiment Analysis

Sentiment Analysis is the process of determining whether provided text is positive, negative or neutral.

It can be determined at both the document and/or entity level and can also show emotional states such as Anger, Disgust, Fear, Joy and Sadness.

Due to the high volume of data today, most sentiment analysis is done using statistical techniques and machine learning however, it's possible to do this using manual processing or keyword processing as well.

### Social Media Analysis

Social media analysis is the biggest use case for sentiment analysis.

It can be used to help companies determine their marketing strategy or see how successful their marketing campaign is.  For example, Expedia Canada noticed an increase in negative feedback due to the music chosen for one of their ads.

It can help companies improve customer service by monitoring sites like Trip Advisor or Yelp for negative reviews and implementing changes based on those comments.

It's used a lot in politics to gauge public opinion to different policy announcements, campaign messages, debates, etc.

### Limitations

Sentiment Analysis is still relatively new and therefore has some limitations.

A machine doesn't have the ability to understand how context affects tone.  Ex. It might see "My flight's been delayed.  Great!" as a positive statement even though it's clearly sarcastic and should be a negative statement.

A machine may also have a hard time understanding acronyms or slang (especially when the word has a double meaning like "sick").

## Demo Links

- [IBM AlchemyLanguage](https://alchemy-language-demo.mybluemix.net)
- [Google Natural Language](https://cloud.google.com/natural-language)
- [Intellexer](http://demo.intellexer.com)

## Other Resources

- https://en.wikipedia.org/wiki/Natural_language_processing
- https://www.revinate.com/blog/2015/10/three-practical-uses-sentiment-analysis/
- http://blog.algorithmia.com/introduction-natural-language-processing-nlp/
- https://www.brandwatch.com/blog/understanding-sentiment-analysis/
- https://www.linkedin.com/pulse/importance-sentiment-analysis-social-media-christine-day

## [License](LICENSE)

Source code distributed under the MIT license. Text and other assets copyright
General Assembly, Inc., all rights reserved.
