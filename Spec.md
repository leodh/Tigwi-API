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

    <MessageList size="sizeOfList">
	    <Message> <!-- See below --> </Message>
	    <Message> ... </Message>
	    ...
	    <Message> ... </Message>
    </MessageList>

Message format:

     <Message>
	     <id> idOfMessage </id>
	     <post_time> timeOfPost </post_time>
	     <poster> nameOfUser </poster>
	     <content> content </content>
     </Message>

###Informations
* In **URL**, _name_ is the name of the user whose messages you want to get.
* In **URL**, _numberOfMessages_ is the number of messages you want to get. It is optional and default is set to 20.
* In **Response**, _sizeOfList_ is the number of messages returned (different from _numberOfMessages if there are not enough messages to provide).

##Get someone's suscriptions list

##Get someone's suscribers list


#Send informations to one's Tigwi account

##Post a message

##Suscribe to someone's  channel