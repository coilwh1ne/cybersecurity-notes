# DNS (Domain Name System)

### What DNS is?

DNS (Domain Name System) - simply way to communicate in the Internet, similar a telephone book. To remember all IP addresses to visit a web-site, connect to a server etc, not nesesary - DNS contains related IP addresses and URLs.

When we want to visit a google.com, we shouldn't remember the IP address this site, we can write ```google.com``` in URL line in browser and visit the site, this is result of work Domain Name System.

---

### DNS Hierarchy

There are a lot of levels in DNS hierarchy, here are some of them:

1. Root domain
2. Top-Level Domain (TLD)

   TLD is most righthand part of domain. For example, in ```google.com``` TLD is ```.com```.
   There are 2 types of TLD:
   gTLD (generic Top-Level Domain) and ccTLD (country code Top-Level Domain),
   > for example .com, .gov, .edu - gLTD, but .ca - ccLTD of Canada
   
3. Second-Level Domain

   Return to example with ```google.com``` - ```google``` is second-level domain

4. Subdomain

   Subdomain is lefthand part of second-level domain, this domain second-level domain creates it himself

---

### DNS Record Types

There are a lot of DNS record types, here are some of them:

1. A records

   These records resolve to IPv4 addresses, for example 104.26.10.229

2. AAAA records

   These records resolve to IPv6 addresses, for example 2606:4700:20::681a:be5
 
3. CHAME records

   A CNAME record (Canonical Name) is a DNS record that points one domain name to another. It is used as an alias (a nickname) for a website.

4. MX records

   MX record tells the internet where to send emails for your domain. Without it, you cannot receive emails on your domain

5. TXT records

   TXT record is used to add any text information to your DNS. Computers read this text to verify that you own the domain and to block spam.




