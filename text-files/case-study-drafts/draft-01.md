# Design Case Study Netflix

Netflix has countless movies and TV shows available for streaming with many different catagories that are tailor made for your personal preferences. One of the categories the service uses relates to what holiday is coming up next on the calendar. (Christmas Movies, Halloween Movies, Valentines Day Movies). Netflix also has hundreds of different TV shows available for streaming all of which have designated holiday episodes. These episodes are usually spread across multiple different seasons.

### What I want to create:
A stand alone section in the Netflix ecosystem that highlights the different Holiday themed TV episodes in one place. Usually a Christmas TV episode is a standalone episode and doesn't relay on a great narrative.

-------

## Research 
Culling of the data for the most famous (American) TV series that have holiday episodes and documenting them. Given that there is hundreds of different TV shows out there I decided to focus on these ten series and only highlight Christmas episodes.

1. The Office (7 Episodes)
2. Frasier (8 Episodes)
3. Simpsons (16 Episodes)
4. Friends (8 Episodes)
5. The Big Bang Theory (3 Episodes)
6. How I met your Mother (7 Episodes)
7. Seinfeld (3 Episodes)
8. Community (4 Episodes)
9. Fresh Prince (3 Episodes)
10. 30 Rock (6 Episodes)

After some simple research, scoping this to just include Holiday episodes is very limiting and at the most basic level the problem is collection/playlist creation. 

-------

## Collections WIP
Stepping back from the problem and thinking of it as a whole. What would be good to setup is a `playlist` model. Playlist is usually reserved and accepted for music, so using the term `collection` would be better. Essentially this problem is delivering a collection of episodes. These can be user generated, netflix generated or 3rd party generated. Starting with Netflix generated collections is probably the easiest MVP for the feature since it will not require editing, adding, and creating. 3rd party will require tool integration and company accounts. User generated is the most complex because it needs to be 100% effortless and pleseant to use

Battle Plan:
1. Netflix Generated – Creates the building blocks and suggests collections based on watching habits. Looks for you most popular `watch & repeat` series and culls from those.
2. Third Party – Outside sources like create collections for a purpose outside tailoring to the users watching habits. Oscar collection, Director Collection, Topic Collection. This would require outside companies to work with Netflix
3. User Generated – Similiar to creating a music playlist. This would be perfect for people that hate certain episodes of a series (I hate "The Fly" Breaking Bad and r/cantwatchscottstots). This will be fully customizable and give super users the ability to cull their likes.


--------




### Important Links
#### Flix Tape (https://flixtape.netflix.com/)
A netflix created standalone app to help the user create playlists for topics

Articles About it:
- https://www.theverge.com/2016/7/15/12201082/netflix-flixtape-movie-playlists-mixtapes
- https://bgr.com/2016/07/15/netflix-playlist-flixtape-how-to-guide/
- https://www.pcmag.com/news/346167/create-a-netflix-playlist-with-flixtape

#### User Needs:
- https://www.reddit.com/r/netflix/comments/8yumcm/i_wish_there_was_a_way_to_make_playlists_of/



## Option 01 (In your face)

### 25 Days of Christmas Advent Calendar Option.
Having just a bunch of different options at you disposale without any context feels very cold. Adding in an element of fun and structure seems more in the nature of the celebration. Christmas already has a whole 25 days of tradition tieing back to the advent calendar. Adding in a checklist approach to keep you watching every night. You can spice in movies as to break up the days.

The list can be populated by what is popular and highest rated by users and also work off of your personal tastes. The list would need to be adaptive to missing days or wanting to skip ahead, and account for all edge cases. Like benge watching. 

## Option 02 Integrated Side Scroll component
A less invasive option would be for people that `watch & repeat` series. Example: My wife and I always have a running pass going of The Office. Those users will get prompted a `side-scrolling` list of options for holiday episodes for that series. This option could ranger from 2 episodes _(Seinfeld)_ – 7 episodes _(The Office)_. There would be quite a few edge cases for this option




Netflix has countless movies and TV shows available for streaming with many different catagories that are tailor made for your personal preferences. One of the categories the service uses relates to what holiday is coming up next on the calendar. (Christmas Movies, Halloween Movies, Valentines Day Movies). Netflix also has hundreds of different TV shows available for streaming all of which have designated holiday episodes. These episodes are usually spread across multiple different seasons.

### What I want to create:
A stand alone section in the Netflix ecosystem that highlights the different Holiday themed TV episodes in one place. Usually a Christmas TV episode is a standalone episode and doesn't relay on a great narrative.