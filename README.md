# pflogsumm

## Postfix log entry summarizer

pflogsumm is designed to provide an over-view of postfix activity, with just enough detail to give the administrator a "heads up" for potential trouble spots.

Changed to summerize postmulti instances, the name should start with postfix-<id>.
  
### Installation
  sudo cp pflogsumm.pl /usr/local/bin/pflogsumm  
  sudo chmod 755 /usr/local/bin/pflogsumm
  
### Usage
  sudo pflogsumm /var/log/mail.log
