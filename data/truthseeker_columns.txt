Dataset Column Information:
--------------------------------------

---Features_For_Traditional_ML_Techniques---

majority_target - Truth value of the tweet
statement - Headline of a new article
BinaryNumTarget - Binary representation of the statement's truth value (1 = True / 0 = False)
tweet - twitter posts related to the associated manual keywords
unique_count - number of unique, complex words.
present_verb - number of present tense verbs.
followers_count - number of followers.
total_count - total number of words.
past_verb number of past tense verbs.
friends_count - number of friends.
ORG_percent - Percent of text including spaCy ORG tags.
adjectives - number of adjectives.
favourites_count - number of favorites across all tweets.
NORP_percent - Percent of text including spaCy NORP tags.
pronouns - number of pronouns.
statuses_count - number of tweets.
GPE_percent - Percent of text including spaCy GPE tags.
TO’s - number of to usages.
listed_count - number of tweets the user has in lists.
PERSON_percent - Percent of text including spaCy PERSON tags.
determiners - number of determiners.
mentions - number of times the user was mentioned.
MONEY_percent - Percent of text including spaCy MONEY tags.
conjunctions - number of conjunctions.
quotes - number of times the user has been quote tweeted.
DATA_percent - Percent of text including spaCy DATA tags.
dots - number of (.) used.
replies - number of replies the user has.
CARDINAL_percent Percent of text including spaCy CARDINAL tags.
exclamations - number of (!) used.
retweets - number of retweets the user has.
PERCENT_percent - Percent of text including spaCy PERCENT tags.
question - number of (?) used.
favourites - number of favourites the user has.
ORDINAL_percent - Percent of text including spaCy ORDINAL tags.
ampersand - number of (&) used. 
hashtags number of hashtags (#) the user has used.
FAC_percent - Percent of text including spaCy FAC tags.
capitals - Number of capitalized letters.
URLs - number of URLs the user has posted.
LAW_percent - Percent of text including spaCy LAW tags.
quotes - number of quotation marks ("") used.
BotScoreBinary - Binary score whether the user is considered a bot or not.
PRODUCT_percent - Percent of text including spaCy PRODUCT tags.
digits - number of digits (0-9) used.
cred - credibility score.
EVENT_percent - Percent of text including spaCy EVENT tags. 
long_word_freq - number of long words.
normalized_influence - influence score the user has, normalized.
TIME_percent - Percent of text including spaCy TIME tags.
short_word_freq - number of short words.
LOC_percent - Percent of text including spaCy LOC tags.
ORG_percent - Percent of text including spaCy ORG tags.
WORK_OF_ART_percent - Percent of text including spaCy WOA tags.
QUANTITY_percent - Percent of text including spaCy QUANTITY tags.
LANGUAGE_percent - Percent of text including spaCy LANGUAGE tags.
Max Word - length of the longest word in the sentence.
Min Word - length of the shortest word in the sentence.
Avg Word Length - average length of words in the sentence.


---Truth_Seeker_Model_Dataset.csv---

author - The author of the statement.
statement - Headline of a new article.
target - the groundtruth value of the statement.
BinaryNumTarget - Binary representation of the target value (1 = True / 0 = False).
manual_keywords - manually created keywords used to search twitter with.
tweet - twitter posts related to the associated manual keywords
5_label_majority_answer - majority answer using 5 labels (Agree, Mostly Agree, Disagree, Mostly Disagree, Unrelated)
3_label_majority_answer - majority answer using 3 labels (Agree, Disagree, Unrelated)

*NO MAJORITY indicates that there was no consensus when a majority answer was generated