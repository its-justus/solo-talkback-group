Notes

Chat App

Base Idea
- Finding small 7-8 user chat rooms
- Based on a subject

General Flow
1. log in (need an account) --> they will be able to see their profile
Profile: recent topics, logs of previous chat rooms as long as they were in the chat
Their favorites, gives them a link to a certain topic
2. --> topic selection page
  * search for a topic, see popular topics in your area
    what's popular in general
  * based on selection, throws you in chat room
  * talk with random people!
  * chat rooms are not meant to be permanent 
    --> if people let them go silent, then they will disappear
3. Chat 
   Display who is in the chatroom
   Textbar at the bottom
   Allow users to react to comments
   Standard chat interface
   Can call a vote to kick someone out (goes by majority)
    --> that person won't be able to get back in or view logs
4. Admin
   * people can report a user
   * then account just gets banned

Frontend --> React, bootstrap for UI
Backend --> postgres, node

Stretch Goals
Maybe webhooks? for pushing notifications?
Table encription
Relationship tracking/building between users
 --> seeing how they interact, content analysis 

Database
* User profiles table
* Table that logs conversations

How will you monitor innapropriate users? 