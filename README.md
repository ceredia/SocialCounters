# SocialCounters
Display social media counters. Twitter followers, Facebook likes, Instagram Followers, Google Plus Followers, LinkedIn connection, YouTube subcribers, Vine followers, Pinterest followers, Dribbble followers, SoundCloud followers, Vimeo followers, GitHub followers, Behance followers, VK followers, Foursquare friends.
##Instructions
* The Twitter and Vine counters require PHP to work, all other counters only require jQuery. 
* Due to the update to the Instagram API after June 1, 2016 you can only access your own photos and profile information using the access token you create.
* After uploading all files to the server, you might need to change this in the api.js for  Twitter and Vine. Change ../SocialCounter/twitter/index.php to http://yoursite.com/SocialCounter/twitter/index.php to include the path to your domain.
* Most of these counters require either access tokens, client id or keys. You need to create these keys in order to display a value.
* In the index.html, place your username and tokens inside the single quotes and it should work.

#How To Use
* Use the example html file provided to display your social media stats. Make sure that there is an html tag with a class belonging to a particular counter. The example below only fetches information about soundcloud, you can add up to 15 counters. In the example file, all html classes are provided, so you can just plugin your username and token, you can also remove counters. Every counter has to have its own html class such as facebook, twitter, instagram, etc...
<pre>
<code>
$('#wrapper').SocialCounter({
  soundcloud_user_id: 'USER-ID-HERE',
  soundcloud_client_id:'TOKEN-HERE'
});
</code>
</pre>


* For this particular counter, the soundcloud class must be included, otherwise it will not display anything.

&lt;a class="item soundcloud"></a&gt;

##Edit Demos in Codepen
* http://codepen.io/juanv911/pen/gbgjLe 
* http://codepen.io/juanv911/pen/ozPoaB
* http://codepen.io/juanv911/pen/oYgbjb

