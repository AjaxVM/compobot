# Needed Plugins #
  * logger - basically just log everything that happens in the channel it is in.
  * command parser - a parser for commands from user, of the form /msg Bot DO Command.
> > What commands should this understand? - currently it just takes a QUIT command,
> > but I'm guessing someone might want to make it be the admin of a channel,
> > and then do admin stuff through it, like topic or something...
  * chatter - basically just responds when people send a private message or a msg with the bot's name in it -- VERY BASIC.


# Possible Plugins #
  * advanced chatter  basically import the pyaiml lib and write an ai for it
> > You would need special variations for different channel and stuff - but for pyweek
> > it could hold some general python/pygame/pyglet/whatever info for people -
> > and then discuss games with them ;)
  * PSR game - Paper, Scissors, Rock -- basically, request a game with each member of a chat room - if they reject pas - otherwise play a game. Also allow users to request a game. Just to make sure the plugins have full functionality.