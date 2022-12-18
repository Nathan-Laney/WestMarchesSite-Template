# Westmarches Site 
### Background Info:
A website to be used to host a West Marches style D&D campaign. This campaign is defined by having between 20 and 50 members, all playing in one universe (the number of players does not need to be enforced).
Players can create an account, and create multiple characters. Some players can be DMs. 
A player or DM will create a post, describing the quest to be completed and how many people it will take to complete it (generally around 4, but can also be a range e.g. 3 to 6) 
Players browse the posts to find a quest. When they find something that is interesting, they put their character’s name down to join the questing party. 
When the quest meets the required number of people, the job becomes inaccessible for others to sign up.
After the quest is complete, players have the option to write down what happened to share with the people that were not on the quest. If they choose to do so, they gain a one-time character buff called Inspiration. The amount of Inspiration a player can have is unlimited, but is limited to characters, not players. 

### Requirements:
- CRUD for:
  - Players (aka users)
  - Characters
  - Jobs
  - Writeups
- Users can create accounts using email. 
- Users can create multiple characters. 
- Users can create posts, aka job listings. 
- Posts are viewable from any account (optionally, also from no account)
- Users can sign up to a job, with a character. 
- Only one character can be assigned to a job per user. (i.e. one person cannot play in a job with two characters)
- Users can create a writeup and post it for others to view
- Posting a review adds one use of Inspiration for that character
### Stretch Goals (Can be implemented however you choose):
- Multiple DMs can exist  
  - Should be one DM per job, and DMs cannot also play in that job as a character
- Players can share a map 
- Users can schedule a time to meet up to complete a job
- Writeups are reviewed for quality before giving inspiration
- DMs can post info only viewable by other DMs
- An out-of-character channel for people to help others with character creation
- An info page giving users data on the campaign rules or setting
- Allow for multiple campaigns (i.e. different accounts can see different sets of posts / characters / writeups, based on which campaign they are in.)
  - Sub-goal: CRUD for campaigns
  - Sub-goal: One user can be in more than one campaign
- Players have a ‘Profile’ page
- Characters have a ‘Profile’ page

### Prizes
TBA
