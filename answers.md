# Answers

Nom: VALTON 
Prénom: Stephane
NB: 4

## 1.3
command: docker build -t tp2back 
docker run tp2back

## 1.4
answer: Car les ports TCP ne sont pas ouverts
command: docker run -p 8080:8080 tp2back

## 1.5
command: docker run -p 8080:8080 -e ENVIRONMENT=dev tp2back 

## 1.6
answer: l'mage n'a pas de tag donc il faut lui en associer un
command: docker tag tp2back steph1101/tp2back

## 1.7
answer:
command: docker rmi -f $(docker images -a -q)
command: docker run -p 8080:8080 -e ENVIRONMENT=dev steph1101/tp2back
command: docker run -d -p 8080:8080 -e ENVIRNEMENT=dev steph1101/tp2back

## 1.8
answer:le nom de mon container est nifty_hypatia
command: docker ps
command: docker rename acd0f160d747 tp2back

## 1.9
answer: Debian 9 (stretch)
answer:PRETTY_NAME="Debian GNU/Linux 9 (stretch)"
NAME="Debian GNU/Linux"
VERSION_ID="9"
VERSION="9 (stretch)"
ID=debian
HOME_URL="https://www.debian.org/"
SUPPORT_URL="https://www.debian.org/support"
BUG_REPORT_URL="https://bugs.debian.org/"


## 1.11
command: 

## 2.1
command: 

## 2.6
command: 
command: 


