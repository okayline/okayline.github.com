♡
## Blog Title: [<ins>How to Completely Lose Your Mind Over Clouds</ins>]
***A Cool Crazy Cyberpunk Guide To:*** *Linux VPS / Cloud Hosting and Services / Self-Hosting / FOSS Apps*
<br><br>

<img width="50%" height="50%" alt="new GITS anime coming out soon!  this is the 'cyberpunk' part of the page" src="https://github.com/user-attachments/assets/1e96d0db-be60-4a13-87a6-046a015878d8" />

<br><br>
#### ✨ June 26, 2026
##### *@15:40* - Lol Blogging on Github.<br>
##### Okay well today is "Learning About Markdown Day" because writing this blog is the first time I'm ever doing MD.  It's a good reason to learn!<br><br>So for the past week or so I've been deep in this Cloud Services and Apps rabbit hole.  And learning so much every day, learned how to launch containers from Portainer, setting up Nginx Reverse Proxy, and now super into self-hosting some apps.  I even signed up for a Github account after years and YEARS of using it without one, signed up just to learn about integrating it with S3 buckets and workers.<br>
##### The purpose of this blog is to dump my brain about all the stuff I've been learning about and experimenting with lately!  The blog format is to try to keep it somewhat focused, hopefully there will be entries about topics like "Free Cloud Hosting Providers" or "SQL and PostgreSQL Hosting".  But for now basically just braindumping/infodumping.<br>
##### Today's project is re-installing NextCloud , for the third (?) day in a row.  Spent one day trying to get it to use a Neon.com PostgreSQL database as the backend.  Then another day trying Cloudflare D1, and realizing that Nextcloud doesn't support PostgreSQL OR SQLite as the backend.<br>The amount of times I've destroyed a Volume and Container , and recreated it for Nextcloud is probably in the dozens.  And planning on doing it a few more times today (hopefully not too many).  Just troubleshooting, solving problems, but always making progress towards a concrete goal, which feels really good!
##### After trying to install NextCloud with the local SQLite backend and "occ convert-db:pgsql" MULTIPLE times , spending HOURS on this, the solution of "host the MySQL or mariaDB locally" came to me last night.  So that is where I'm at today, going to start with : ***(learning about and how to) install MariaDB***<br><br> <sup>(A Short time Later...)</sup>  
##### *@19:32* - Okay I set everything up!<br><br>Set a MariaDB docker container up , used it as the Nextcloud backend on initial install, External Storage plugin and connected Cloudflare S3 and WebDAV.  Thinking about connecting up Google Drive.  Am currently in the process of having Nextcloud back itself up.<br><br>Speaking of backing up, my next project is ***Rclone*** (uh oh!)<br>

##### Also I'm very happy that you can use normal HTML tags in MD and it works!  So it truly feels like blogging by writing/hacking together an HTML file in Notepad back in the day.

##### Listening to <a href="https://www.youtube.com/watch?v=H1d_aEantvc"><ins>Memory System | Ambient Swim | Liquid DnB, Jungle, Breakcore</ins></a>,   Feeling <sub><a href="https://www.imood.com/users/kayline"><img width="60" height="15" alt="68747470733a2f2f6d6f6f64732e696d6f6f642e636f6d2f646973706c61792f756e616d652d6b61796c696e652f696d6f6f642e676966" src="https://github.com/user-attachments/assets/a87efe2f-bad3-434d-ab5e-67e53635a981" />

<br>

#### ✨ June 25, 2026
##### *@20:20* - This is sort of an inelegant approach, just directly writing everything directly on the README.md, but it works!

<br>

#### ✨ Content
##### Write your amazing content here...

<br><br>

##### okayline.github.com | This page was created using a modified template from https://mdkit.io/templates/blog-post-draft | Last updated by hand at 19:45 June 26, 2026
