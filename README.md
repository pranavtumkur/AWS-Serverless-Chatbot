# Amazon-Serverless-Chatbot

An AWS Lex based chatbot which assists you to Book a Trip. This chatbot is split into 2 parts, both important legs of any trip, viz.-
1. Booking a hotel
2. Booking a car

This chatbot commbines services like Amazon Lex, Polly, Lambda, Dynamo DB and Cloudwatch Logs to give you a wholesome experience!

![Screenshot (364)](https://user-images.githubusercontent.com/65482013/101245382-7b369800-3732-11eb-8cd1-2f6a4ebda6cf.png)

Following are how each of these services are put to use in the chatbot context-
1. AWS Lex- Using ML, NLP to convert user text to fill understand instances and full the necessary slots.
2. AWS Polly- To convert text to speech and speech to text for when you feel bored to type out your request
3. AWS Lambda- Validating the user entries and filling in fields as per the database in Dynamo
4. Dynamo DB- Maintaining a master of cities, car types, prices pertaining to our car and hotel services
5. Cloudwatch Logs- To track usage of the chatbot and account for instances are chatbot was unable to cater to

Last but not the least, this chatbot has been hosted on Facebook for all my peers to try out! Do try it out and let me know your feedback- [My Serverless Chatbot for Booking a Trip](https://www.facebook.com/Serverless-Chatbot-for-Bookings-100106728625497)

Thanks!
