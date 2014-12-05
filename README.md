Chat Server
============

Description
----
##### Chapter 14, The Well Grounded Rubyist
Implementing a chat server which keeps an array of all incoming connections, which is then used to broadcast all incoming chat messages to.

Exercise objectives
----
Exploring the syntax and semantics of threads and how they facilitate projects such as multi-user networked communication.

How to run it
----

```sh
git clone git@github.com:sroop/threaded_chat_server.git
cd threaded_chat_server
ruby chatserver.rb
```
Open up a new tab and connect as a user:

```sh
telnet localhost 3939
```

Open up another tab to connect as a second user:

```sh
telnet localhost 3939
```

Happy chatting!