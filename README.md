openjsip
========

Open Java SIP - opensource SIP services implemented in Java ( SIP Proxy, SIP Registrar etc. )

About
OpenJSIP is a GNU GPL licensed bundle of free distributed SIP services run by Java VM.
Distributed means that these services can be deployed on different hosts communicating with each other with the help of Remote Method Invocation (RMI). Distributed architecture allows creation of redundant and load-balanced systems.

At the current stage of development (v0.0.4) the project includes:

SIP Proxy
Statefull operation
Stateless operation
SIP Registrar
Standalone (can listen to requests itself)
ViaProxy (proxy listens to requests and deliver registrations to registrar)
SIP Location Service
No database integration. Keeps data in memory (for now)
OpenJSIP is based on SIP stack provided by JAIN-SIP project. Thanks to all the authors for this incredible work.

https://code.google.com/p/openjsip/
