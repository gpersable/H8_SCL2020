# Natural Language Processing and Sentiment Analysis Introduction
Author: Raka Ardhi
## Brief Introduction to NLP
Computers are great at working with structured data like spreadsheets and database tables. But us humans usually communicate in words, not in tables. That’s unfortunate for computers 😢


According to industry estimates, only 21% of the available data is present in structured form. Data is being generated as we speak, as we tweet, as we send messages on Whatsapp and in various other activities. Majority of this data exists in the textual form, which is highly unstructured in nature. Few notorious examples include – tweets / posts on social media, user to user chat conversations, news, blogs and articles, product or services reviews and patient records in the healthcare sector. A few more recent ones includes chatbots and other voice driven bots. Despite having high dimension data, the information present in it is not directly accessible unless it is processed (read and understood) manually or analyzed by an automated system.

Based on information given above, lot of information in the world is unstructured — raw text in English (or bahasa) or another human language. How can we get a computer to understand unstructured text and extract data from it? Can Computers Understand Language?

   > Natural language processing (NLP) is a subfield of linguistics, computer science, information engineering, and artificial intelligence concerned with the interactions between computers and human (natural) languages, in particular how to program computers to process and analyze large amounts of natural language data. - Wikipedia

So, in short; Natural Language Processing, or NLP, is the sub-field of AI that is focused on enabling computers to understand and process human languages. With the help of a Bunch of Algorithms and rules the computer able to understand and communicate with humans in vast human languages and scales other language-related tasks. With NLP, it is possible to perform certain tasks like Automated Speech and Automated Text Writing in less time. Due to the evolving of large data (text), why not to use the computers which have high computing power, capable of working all day and ability to run several algorithms to perform tasks in no time.

NLP can be divided into 3 categories (Rule-based systems, Classical Machine Learning models and Deep Learning models).

1. Rule-based systems rely heavily on crafting domain-specific rules (e.g: regular expressions), can be used to solve simple problems such as extracting structured data (e.g: emails) from unstructured data (e.g: web-pages), but due to the complexity of human natural languages, rule-based systems fail to build models that can really reason about language.
2. Classical Machine Learning approaches can be used to solve harder problems which rule-based systems can’t solve very well (e.g: Spam Detection), it rely on a more general approach to understanding language, using hand-crafted features (e.g: sentence length, part of speech tags, occurrence of specific words) then providing those features to a statistical machine learning model (e.g: Naive Bayes), which learns different patterns in the training set and then be able to reason about unseen data (inference).
3. Deep Learning models are the hottest part of NLP research and applications now, they generalize even better than the classical machine learning approaches as they don’t need hand-crafted features because they work as feature extractors in an automatic way, which helped a lot in building end-to-end models (little human-interaction). Aside from the feature engineering part, deep learning algorithms learning capabilities are more powerful than the shallow/classical ML ones, which paved its way to achieving the highest scores on different hard NLP tasks (e.g: Machine Translation).

## Extracting Meaning from Text is Hard
The process of reading and understanding English (or bahasa) is very complex — and that’s not even considering that English (or bahasa) doesn’t follow logical and consistent rules. For example, what does this news headline mean?

   > "Environmental regulators grill business owner over illegal coal fires."

Are the regulators questioning a business owner about burning coal illegally? Or are the regulators literally cooking the business owner? As you can see, parsing English with a computer is going to be complicated. Another challenge are listed below:

1. Ambiguity / Crash Blossom  
It is the challenge when a Single word has different meanings or a sentence that has different meanings in the context and even a sentence refers to sarcasm.
   * Lexical Ambiguity is the presence of two or more possible meanings within a single word. (ie. I saw her duck)
   * Syntactic Ambiguity is the presence of two or more possible meanings within a single sentence or sequence of words. (ie. The chicken is ready to eat)
2. Syntax  
Think of how a sentence is valid, it based on two things called syntax and semantics where syntax refers to the grammatical rules, on the other hand, semantics is the meaning of the vocabulary symbols within that structure. People change the ordering of sentences it is valid in some cases but not all.
3. Co-reference / Anaphora Resolution  
The problem of resolving what a pronoun, or a noun phrase refers to. (ie. Hacktiv8's employee took two trips around France. They were both wonderful.)
4. Slang  
5. Sarcasm  
Same words different meaning refers to the Ambiguity topic. Suppose when someone does something wrong you reply as very good or well done. it’s also a challenge for a computer to understand the sarcasm because it’s a way more different than a normal conversation.

## Applications of NLP
- Machine Translation
- Information Extraction
- **Sentiment Analysis**
- Information Retrieval
- Question Answering
- Summarization
