# InstaBruteForcer
Instaghost is an Shell Script to perform multi-threaded brute force attack against Instagram, this script can bypass login limiting and it can test infinite number of passwords with a rate of about 1000 passwords/min with 100 attemps at once.

#Legal disclaimer:
---
Usage of InstaGhost for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program

#Features
---
-Multi-thread (100 attempts at once)

-Save/Resume sessions

-Anonymous attack through TOR

-Check valid usernames

-Default password list (best +39k 8 letters)

-Check and Install all dependencies

#Usage:
---
```txt
  git clone https://github.com/Pranav-V-20/instaghost
  cd instaghost
  chmod +x instaghost.sh
  sudo ./instaghost.sh
```

Install requirements (Curl, Tor, Openssl):

```txt
chmod +x install.sh
sudo ./install.sh
```

#How it works?
---
Script uses an Android ApkSignature to perform authentication in addition using TOR instances to avoid blocking. The script uses Instagram-py algorithm (Python), see the project at: https://github.com/antonyjr/instagram-py 
