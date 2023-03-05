A site where users can register and customize accounts, log in, create and manage threads/topics, post and delete comments, like other users comments, and view other users profiles

Threads, or "Spaces," are places where users can post comments and pictures. Comments are displayed in descending chronoligcial order, mening newest comments are at the top. On the home page, the most recently active threads will appear at the top, just below any threads that are pinned.

This site uses SSID based user autherntication to keep track of logged in users and to verify permissions whenever a user tries to change or add data, like posting a new comment. Some users are designated as "Administrators," which can be seen on their account page. These users may delete any comment, and are able to view and restore comments that have been deleted, all from the website itself, rather than from a database.

Passwords are ancrypted and then stored in the database. Passwords only need to be sent over the network upon registration and when logging in. In all other cases, the session ID for that users current session is sent, along with their username, to validate that the user is currently logged in.

Threads can be locked, archived, or deleted by their respective creators, or by site administrators.

I have many features planned for this site, some of which can be viewed on the site itself! The thread titled "Dylans Notes" has some ideas for additions or modifications. I plan on updating the appearance and making the UI more consistent soon!

This site was created using the React JavaScript framework. The backend API is a NodeJS server, which provides the site with access to the mySQL server.

Languages/Frameworks:
-JavaScript
 -React
 -NodeJS
-HTML
-CSS
-SQL

Users can set a unique username, but they can also set a custom "Display Name." The name can have emojis or other special characters, meaning users can have fun nicknames, but can still log in with their plane-text username. The color of the users display name can also be changed by entering a color hex-code!

 ![image](https://user-images.githubusercontent.com/98580719/222946444-e10f4513-e8bf-4541-8be1-63e86446b57d.png)

The thread management section, viewed as an Administrator

 ![image](https://user-images.githubusercontent.com/98580719/222946447-fcead859-50eb-491b-9c6e-6c76a0cb3323.png)

Comments can be posted and deleted. Admins can still see deleted comments, as well as restore them.

 ![image](https://user-images.githubusercontent.com/98580719/222946471-69c9ac9d-9c24-47ad-b2db-5d6b3aa51f74.png)

The home page shows the threads, orderd by "pinned" status, and then by most recent activity
 

