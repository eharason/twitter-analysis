# Twitter-analysis
display #stayAtHome tweets

This repo contains the complete code for what was covered in the [FTL Hackathon](https://bigdatahack.femaletechleaders.org/) **Intro to Big Data: COVID-19 and its Global Effects** [Twitter API Workshop](https://github.com/yoanad/ftl-twitter-workshop)

## Steps

1. Clone this repo
1. Create a new app in your [Twitter Developer Account](http://developer.twitter.com/)
   1. If you do not have a Twitter Developer Account, please ping one of the mentors who will add you to our Twitter **FTL Hackathons Team** Developer Account. You'll just need to provide us with your twitter handle
1. Create a `twitterConfig.js` file at the same level as `server.js` with the following contents (from that app you created in #2):

```javascript
module.exports = {
        consumer_key: 'your_consumer_key',
        consumer_secret: 'your_consumer_secret',
        access_token: 'your_access_token',
        access_token_secret: 'your_access_token_secret',
}
```
4. Install dependencies and run the server!
```
npm install
node server.js
```
5. Navigate to `localhost:3000`. You should see an HTML page with all of the popular and latest tweets for that hashtag

## What's next?

- Use this repo as a starting point to take this track to the next level!
- Consider ways you can iterate upon it in order to visualize tweets
- Inspiration: Check out the USC Melady Lab's [COVID-19 Tweet Analysis](https://usc-melady.github.io/COVID-19-Tweet-Analysis/)
