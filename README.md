# WATCH-IT-Data-Base-Project
WATCH IT is a video on-demand service for Arabic content online. With an exclusive collection of various entertainment options of movies and TV . <br>
●	We store for each user( name , password ,email , birthdate ). <br>
     ■	Age will be calculated.  <br>
●	We store for each subscription (payment amount , period , date , number of screens  , bank card). <br>
     ■	expire date will be calculated. <br>
●	We store for each content( id , name , age limit , details ,rate , release date , seasons , type ).
■	Content divides into (movies ,series , shows).
■	Each series and show contains episodes (duration, number).
➔	Each user has a subscription [1 : 1 relation] 
◆	(one user has one Subscription  and one Subscription has one user).
◆	user should has subscription.
➔	Subscription provides content [m : n relation] 
◆	(one Subscription provides many contents one content provides          many  Subscriptions).
◆	subscription should has content and vice versa . 
➔	 Series contains episode [1:  m relation]
◆	(one series contains many episodes and one episode contains one series).
◆	Series should has episodes and vice versa.
➔	Shows has episode [1:m]
◆	( one show has many episode and one episode belong to one show). 
◆	Shows should has episode and vice versa.
➔	User searches for content [m : n relation] (  one user searches for content, and the same content is searched for by many users ).
