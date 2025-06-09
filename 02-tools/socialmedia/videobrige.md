A place that you can upload content and push that content to many social media network.
You can manage many social accounts and try to upload content to many social.
Some main features for videobrideg.
 + Login from google.
 + posts to many social media
 + Make scheduled post to many social media.
 + List posts 
 + Create post as scheduled, draft or posted
 + Call api Gemini to get some ideas for creating posts.

 Supabase support all session on this website from login at third-part to edge function
 Edge function run every 1 minute to check all posts at scheduled status ==> Posted and upload to all platforms

 Using cron active on github to call edge function supabase for posting after 1 minute.
 If posting success, the status will change from scheduled to posted and show on dashboard.

In dashboard , we have two seperate . It is sidebar and main dashboard.
We have a modal in this to create new post. You can see it highlight with blue color and when you click on
One modal show up and let type some information for this textarea and add emoji on below navs.



