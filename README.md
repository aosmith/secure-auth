secure-auth
============


secure-auth is a kernel based authentication module that relies on usb drives
for large self signed certificates.


High Level Overview
--------------------

Passwords don't work.  The cryptanalysts are winning.  Instead of relying on
weak password we should utilize 2 or more keychain style usb sticks.  On these
usb drives we can store very large, and very difficult to crack, self signed
security certificates.  Theses certificates could be utilized at multiple
layers, be it OS authentication or web based service authentication.
