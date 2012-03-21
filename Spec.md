Tigwi - API Specification by L. de HARO, A. de MYTTENAERE and T. ZIMMERMANN 

#Get an user's public informations

##Get someone's messages
###Objective
Obtain a number _n_ of the user _name_ 's last posted messages
###HTTP method
*GET*
###URL
http://api.tigwi.com/usertimeline/_name_/_numberOfMessages_
###Request
_left empty_
###Response

     <Message>
	     <id> idOfMessage </id>
	     <post_time> timeOfPost </post_time>
	     <poster> nameOfUser </poster>
	     <content> content </content>
     </Messaget>

###Informations

##Get someone's suscriptions list

##Get someone's suscribers list


#Send informations to one's Tigwi account

##Post a message

##Suscribe to someone's  channel