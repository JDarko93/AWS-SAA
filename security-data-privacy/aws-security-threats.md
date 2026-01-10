## AWS Security Threats

### Injection Attacks

- This is when malicious input from a threat actor gets accepted by the web application. It is not input that the web app was designed to accept

### Malicious User Input

1 - Attacker suppliers malicious input
2 - Web app does not properly validate/sanitise user input

### Injection attack types

#### Cross-Site Scripting (XSS)
- This is when a web form doesnt properly validate an input field

#### Host header injection

#### OS command injection
- Once someone receives privileged access to a remote host , they could start executing OS commands. Also through a URL

#### SQL injection
- This could also be done via a URL or search tab on a web page that isnt proeprly validated
- SQL syntax can return outputs from the backend database

#### Denial-of-Service Attacks
- Can render a service unsuable by legitimate users. (Server crash or network flood)
- This usually is done through DoS or DDoS and can cost the company downtime, losing them £££
- This attack can be mitigated by AWS Shield


### Web Application Firewall (WAF)

- A hardware or software application designed to look for web application attacks
- Can prevent and report potential web application injection activity 