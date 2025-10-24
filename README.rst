
PKCS11 Proxy
============

This fork has the following additional features:

- support for running in "inetd mode", useful for calling directly from stunnel
- seccomp syscall filtering (only tested in inetd-mode)
- getaddrinfo support for IPv6, fallback and DNS resolution
- TLS-PSK support to optionally encrypt communication
- OS/X build support 
- PKCS11 v3 support
- EDDSA support

Plus a number of important bug fixes. This version passes the SoftHSM test
suite.
