# FCCAPI-NET

FCCAPI-NET is an API written in C# for Funchatcam chat & services.
You can use it to create bots, services & other nice things using the Funchatcam Client.

### Usage
Reference the dll in your project and code!

If you use this please let us know or if you want to suggest
any new features or requests.

Feel free to create issues for enhancements.

admin@funchatcam.com

#####string get_last_chat_line()
> Returns the last line from chat visible in the client.

#####string get_version()
> Returns FCCAPI-NET version.

#####void handsfree_toggle()
> Clicks the Handsfree checkbox.

#####void mute_toggle()
> Clicks the mute button.

#####void sendchat(string text)
> Sends text to the chatroom.

#####void quit()
> Clicks the signout/quit button.

 ###### TODO
 
 get_users_funtokens
 get_users_chatpoints
 get_users_gender
 get_users_age
  
 server_oplist_clear
 server_oplist_add
 server_oplist_remove
 server_banlist_clear
 server_banlist_add
 server_banlist_remove
 
 room_lastjoined
 room_lastquit
 room_close
 room_permanent
 room_lock
 room_password
  
 kick_user
 punish_user
 ban_user
 friend_user
 ignore_user
 
 lastseen
 timein (tell me the time in a city)
 