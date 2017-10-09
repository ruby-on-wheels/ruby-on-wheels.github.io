---
layout: post
title:  Sharing saved places from Google Maps
date:   2017-10-07
header-img: assets/images/Sharing_saved_places_on_Google_Maps_-_Ruby_on_Wheels.jpg
comments: true
---

I usually save the places where I stay over night in the Google Maps app. It helps me to remember my exact route and is also helpful when I recommend great spots to other van people who I meet on the road. Here is how you can export your saved places from Google Maps and share it with other people in an embedded interactive map on your website:

1. Go to [Google Takeout](https://takeout.google.com/settings/takeout) create an archive that contains your data for Maps (your places) and download the archive:
![Export Google Maps data](/assets/images/Data_tools_-_Download_your_data.jpg)
2. Convert the JSON file from the archive to a KML file using an [online converter](http://nearby.org.uk/convert-saved-places.php).
3. Go to [My Maps](https://www.google.com/maps/d/u/) on the Google Maps website and create a new map.
4. Import the KML file into your map:
![Import places via the KML file](/assets/images/Places_visited_with_my_van.jpg)
5. Optionally you can add, remove or change the markers.
5. Click the preview link to view your map.
6. Press the `SHARE` button and choose "Embed on my site". You might have to change the permission to allow public access before you can expose the map on your website:
![Get the HTML code for embedding the map into a website](/assets/images/Places_visited_with_my_van_share.jpg)
7. Copy the HTML code and paste it into your blog:

<div class="google-maps" style="padding-bottom: 85%">
  <iframe src="https://www.google.com/maps/d/embed?mid=1oJWtlohfxJ_Oa4t3XFDdOOyyJK4" width="750" height="640"></iframe>
</div>

Et voilà, you can share your saved places on your website with an interactive map!
