# Delphi WebSocket Server #

## About this project ##

This project is a Delphi implementation of the WebSocket protocol (server side) and (currently) is compatible with the following WebSocket drafts:

  * raft-ietf-hybi-thewebsocketprotocol-00 (draft-hixie-thewebsocketprotocol-76)
  * raft-ietf-hybi-thewebsocketprotocol-07
  * raft-ietf-hybi-thewebsocketprotocol-08
  * raft-ietf-hybi-thewebsocketprotocol-09

For the client part, an html example file is provided, a Delphi client is also provided but only for testing purpose.

## Project requirements ##

The project is compiled with Delphi XE

The code is currently compatible only with Delphi 2010 and XE.
I've used the RegularExpressions unit but I plan to convert the code with plain string management routines.

The code depends on the Indy 10 library (updated from the SVN repository).

## Project status ##
The project is in its initial stage but it's perfectly usable with current (06-2011) browser's WebSocket implementation.