##just for fun

I'm intended to write an online foo framework, where foo may be "chatting", "game", or others.

C/S model, mysql as the database.

In server.py, I use epoll from Linux, to support multiple tcp sockets.

In client.py, I've implemented the simplest interactive way to communicate with server. all function definitions show the interface of the protocol.

more clearly, protocol.py defines the operations of the protocol(enum --- not pythonic= =?)

There is nothing important in misc.py, true.

If you want more, please stop reading and forget it! the source code is terrible!

