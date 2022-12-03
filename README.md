# **Сетевая безопасность**

**Ссылка на задание/требования:** https://github.com/netology-code/ibqa-homeworks/blob/main/5.%20Network_Security/homework_lecture5.md

**Анализируемый хост:** scanme.nmap.org

Используемая команда: nmap -T4 -A -v scanme.nmap.org

## **Задание 1**

![Количество служб](/Nmap1.png)

Количество сетевых служб, запущенных на указанном хосте: 4

## **Задание 2**

![Web-сервер](/Nmap2.png)

В качестве web-сервера используется: Apache 2.4.7

## **Задание 3**

![ОС](/Nmap3.png)

Скорее всего на сервере используется ОС: Linux версии 5.0-5.4 с вероятностью 97%


## **Задание 4**

![ExpDB1](/ExpDB1.png)

![ExpDB1.1](/ExpDB1.1.png)

![ExpDB1.1](/ExpDB1.2.png)

![ExpDB2](/ExpDB2.png)

Уязвимости, которым подвержен данный сервер (проверено при помощи сайта exploit.db):

- Apache Httpd mod_proxy - Error Page Cross-Site Scripting
- Apache Httpd mod_rewrite - Open Redirects
- Apache 2.4.7 mod_status - Scoreboard Handling Race Condition
- Apache 2.4.7 + PHP 7.0.2 - 'openssl_seal()' Uninitialized Memory Code Execution

