# About Spidey
Spidey is a subdomain enumeration tool, which is uses other subdomain enumeration tools together and serves founded subdomains all together 

# Used tools

You need to install listed tools bellow on your machine, and must contain under executable files directory such as **/usr/bin**. You can visit the links and setup tools on your machine

* Sublist3r -> https://github.com/aboul3la/Sublist3r
* Amass -> https://github.com/OWASP/Amass
* Subfinder -> https://github.com/projectdiscovery/subfinder
* Assetfinder -> https://github.com/tomnomnom/assetfinder

# Usage

| Flag       | Description |
| ----------- | ----------- |
| -d      | Domain name to enumerate subdomains of       |
| -o      | Save the results to text file        |

<pre>
./spidey -d yahoo.com -o subdomains.txt
</pre>

# Version
 0.0.1
