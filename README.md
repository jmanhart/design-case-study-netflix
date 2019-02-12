# Design Case Study Netflix

Netflix has countless movies and TV shows available for streaming with many different catagories that are tailor made for your personal preferences. One of the categories the service uses relates to what holiday is coming up next on the calendar. (Christmas Movies, Halloween Movies, Valentines Day Movies). Netflix also has hundreds of different TV shows available for streaming all of which have designated holiday episodes. These episodes are usually spread across multiple different seasons.

### What I want to create:
A stand alone section in the Netflix ecosystem that highlights the different Holiday themed TV episodes in one place. Usually a Christmas TV episode is a standalone episode and doesn't relay on a great narrative.

-------

## Research 
Culling of the data for the most famous (American) TV series that have holiday episodes and documenting them. Given that there is hundreds of different TV shows out there I decided to focus on these ten series and only highlight Christmas episodes.

1. The Office
2. Frasier 
3. Simpsons
4. Friends
5. The Big Bang Theory
6. How I met your Mother
7. Seinfeld
8. Community
9. Fresh Prince
10. 30 Rock

After some simple research, scoping this to just include Holiday episodes is very limiting and at the most basic level the problem is collection/playlist creation. 

-------

## Collections WIP
Stepping back from the problem and thinking of it as a whole. What would be good to setup is a `playlist` model. Playlist is usually reserved and accepted for music, so using the term `collection` would be better. Essentially this problem is delivering a collection of episodes. These can be user generated, netflix generated or 3rd party generated. Starting with Netflix generated collections is probably the easiest MVP for the feature since it will not require editing, adding, and creating. 3rd party will require tool integration and company accounts. User generated is the most complex because it needs to be 100% effortless and pleseant to use

Battle Plan:
1. Netflix Generated – Creates the building blocks and suggests collections based on watching habits. Looks for you most popular `watch & repeat` series and culls from those.
2. Third Party – Outside sources like create collections for a purpose outside tailoring to the users watching habits. Oscar collection, Director Collection, Topic Collection. This would require outside companies to work with Netflix
3. User Generated – Similiar to creating a music playlist. This would be perfect for people that hate certain episodes of a series (I hate "The Fly" Breaking Bad and r/cantwatchscottstots). This will be fully customizable and give super users the ability to cull their likes.


--------

