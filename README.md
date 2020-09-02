# Indian_Sign_Language
My efforts to make a live video feed translator for indian sign language 


1.First of all I followed a [tutorial](https://www.digitalocean.com/community/tutorials/how-to-build-a-neural-network-to-translate-sign-language-into-english) by digital ocean on American sign Language classifier

2.I came upon a valuable article from [AI4BHARAT](https://ai4bharat.org/articles/sign-language), I will try to ask them for the video dataset they created, it would be redundant to make a dataset when one already exists.
3. I am thinking of using pyttsx3 module to coonvert the reported text into audio. My main plan is to create a cnn with input from video feed and then adding a simple rnn to combine it into text, this would subsequently be passed through pyttsx3 module to generate voice. Let's hope this works fine. 
