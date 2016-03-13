# pubnubChatAndHangman
Using PubNub's AngularJS SDK, I made this chat app with a small Hangman game (JS code loosely based on: http://codepen.io/offline_blogger/pen/Kedtr). 
For this, I kept it simple (and the following steps are even more simplified.)
* Initiated PubNub by   
  + Creating a free account at https://www.pubnub.com
                        
  + Generating a set of keys: Publish Key and Subscribe Key
* Created a channel (here, it's the DisneyChannel--haha) before subscribing to it. This subscribe function is where received messages are called back to.
* Made up user ID's for those who would use the chat app. Each user is assigned a random letter from the alphabet (this is assuming no more than 26 users will be on--once midterms are over, I will hone this more and fix this!!)
* Created a publish function, which displays messages users type.
* Populated the message history to keep track of old messages, and pre-populated the user list to display the random letters assigned to users on the chat app.

This took more time than I thought because I wasn't sure where to begin! I looked over PubNub's iOS and JS SDKs and documentation, read multiple tutorials, and still did not know what to do (it is midterms-season, after all.) But actually, the sky is the limit with PubNub, and I look forward to using their SDKs in the future for hackathons, side projects, and hopefully classes!

