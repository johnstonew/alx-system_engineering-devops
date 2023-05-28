## Questions
## 1. Where are SPOF
Currently only one web server, database and application server exists.During maintenance or when the site experiences high traffic. The site is likely to go down.
## 2. Security issues (no firewall, no HTTPS)
- Lack of HTTPs means that users data can be intercepted on the way to the server. And used maliciously by the attacker. 
- Not having a firewall means that the server is prone to attacks from hackers.
## 3. No monitoring
No monitoring means that whenver the site eperiences any issues, it is hard for the developer to know what is going on in real time. Or even diagnose what caused an error whenever the site goes down, or if it is slow.