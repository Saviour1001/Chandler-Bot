# Chandler-Bot
Created a chat bot based on Chandler from F.R.I.E.N.D.S 

![Chandler](https://user-images.githubusercontent.com/71517788/123321024-1c126680-d550-11eb-9ba7-32828a5875bf.jpg)

Chandler Bing is my favourite character from the famous sitcom F.R.I.E.N.D.S 
and thus this chatbot is a fun little side project to enjoy and leverage the 
power of machine learning for the purpose of entertainment. 

You could talk with the bot [here](https://huggingface.co/Saviour/ChandlerBot).

# Description 

Our goal is to make a bot which would respond to situations/texts in a way that Chandler would. For 
that I used a dataset which consisted of the transcribed scripts of the complete show F.R.I.E.N.D.S. I 
sorted out the dialogues of Chandler and the context to that dialogue. 

I used the DialoGPT-medium model provided by Microsoft on Hugging Face, and trained it over the 
training dataset i.e. the dialogues of Chandler. As we don't have a way to measure the accuracy of 
a chat bot, I indulged on checking the perplexity of the chat bot which tells how confused the bot is 
about himself. A lower perplexity means a smarter bot. 

The perplexity can be lowered by raising the number of epochs and training it over more clean data,but as of 
now the model has generated a bot of 4.6389 perplexity while it was trained for 10 epochs of 1800 iterations each. 

# Results 

![Chandler Bot](https://user-images.githubusercontent.com/71517788/123322107-7cee6e80-d551-11eb-8e3a-78251e47785b.PNG)

![WhatsApp Image 2021-06-24 at 7 25 21 PM](https://user-images.githubusercontent.com/71517788/123322182-98f21000-d551-11eb-8db0-cf0694ac1c26.jpeg)

![Chandler](https://user-images.githubusercontent.com/71517788/123333180-09535e00-d55f-11eb-9b43-1e7498600323.PNG)



