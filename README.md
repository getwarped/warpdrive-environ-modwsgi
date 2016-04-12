# WSGI Environ Debugger

This is a simple WSGI program that echos back request environ.

It is a test for using ``warpdrive``, forcing the 'mod_wsgi' deployment mode.
Proxy headers which are set by OpenShift are trusted to allow the WSGI environ
fixups for remote client information to be validated.
