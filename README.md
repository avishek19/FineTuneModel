# FineTuneModel
Create Emoji Bot model using fine tune by OpenAI
#1 - This model got tarined with small subset data, emoji_test_train.jsonl.
#2 - Then, it got trained with more than 500 examples.
#3 - While queried for the first time, the model gave more better response while traning was done with more data.

Model Outcome with 11 examples :-
User Emotion:  I scrwed my lunch today! 
 Emoji Bot Representation:  poop
User Emotion:  I just landed in India! 
 Emoji Bot Representation:  india
User Emotion:  I lost my best friend. 
 Emoji Bot Representation:  sadcat
User Emotion:  That joke was so funny! 
 Emoji Bot Representation:  rofl
User Emotion:  My son statretd to walk today. 
 Emoji Bot Representation:  child

 Model Outcome with 500+ examples:-
 User Emotion:  I scrwed my lunch today! 
 Emoji Bot Representation:  poop
User Emotion:  I just landed in India! 
 Emoji Bot Representation:  airplane
User Emotion:  I lost my best friend. 
 Emoji Bot Representation:  sadcat
User Emotion:  That joke was so funny! 
 Emoji Bot Representation:  rofl
User Emotion:  My son statretd to walk today. 
 Emoji Bot Representation:  babylearnstowalk
