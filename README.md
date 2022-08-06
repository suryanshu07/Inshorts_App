# Inshorts_App
Summarization systems often have additional evidence they can utilize in order to specify the most important topics of document(s). For example, when summarizing blogs, there are discussions or comments coming after the blog post that are good sources of information to determine which parts of the blog are critical and interesting.
In scientific paper summarization, there is a considerable amount of information such as cited papers and conference information which can be leveraged to identify important sentences in the original paper.

# The need
With the present explosion of data circulating the digital space, which is mostly non-structured textual data, there is a need to develop automatic text summarization tools that allow people to get insights from them easily. Currently, we enjoy quick access to enormous amounts of information. However, most of this information is redundant, insignificant, and may not convey the intended meaning. For example, if you are looking for specific information from an online news article, you may have to dig through its content and spend a lot of time weeding out the unnecessary stuff before getting the information you want. Therefore, using automatic text summarizers capable of extracting useful information that leaves out inessential and insignificant data is becoming vital. Implementing summarization can enhance the readability of documents, reduce the time spent in researching for information, and allow for more information to be fitted in a particular area.

# How to perform text summarization
Step 1: Convert the paragraph into sentences
First, let’s split the paragraph into its corresponding sentences. The best way of doing the conversion is to extract a sentence whenever a period appears.

Step 2: Text processing
Next, let’s do text processing by removing the stop words (extremely common words with little meaning such as “and” and “the”), numbers, punctuation, and other special characters from the sentences.

Step 3: Tokenization
Tokenizing the sentences is done to get all the words present in the sentences.

Step 4: Evaluate the weighted occurrence frequency of the words
Thereafter, let’s calculate the weighted occurrence frequency of all the words. To achieve this, let’s divide the occurrence frequency of each of the words by the frequency of the most recurrent word in the paragraph, which is “Peter” that occurs three times.
