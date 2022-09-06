---
---

# DNS Server

### Definition
  Responds to queries such as google.com and replies the answer ip address of
  the server that holds google.com

### Types

* Authoritative or Primary Server
* TLD Server
* Root name Server
* Recursive Server

### Recursive Server

* Frequently used
* Gets query from client and if data is present in cache, will reply with answer

### Root Server

* Maintained by ICANN
* Forwards queries to TLD server

### TLD Server

* Maintained by IANA
* 2 Groups
  * Generic TLD - eg. .com, .org
  * Country Wise TLD - eg .in,.cn

### Authoritative Server

* Last leg of DNS query.
* It has answer if all the other cache methods fail.
