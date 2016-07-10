# Heading 1
## Heading 1.1
### Heading 1.1.1
#### Heading 1.1.1.1
##### Heading 1.1.1.1.1

Alternate Heading 1
===================
Alternate Heading 2
-------------------
## Mix two styles of heading 2
### Heading 2.2.1

## Quoting code (any language)
```
git status
git add -A :/
git commit -m 'auto commit'
```

## Quoting python code with syntax highlighting
```python
def myfunc(*args, **kwargs):
  for i in args:
    print i
  for (k, v) in kwargs.items():
    print k, v
```

## Terminal output
```terminal
(try2)sundar@smaug:~/tmp/zeromq$ ls -l
total 16
-rw-r--r-- 1 sundar users 579 Jul  9 19:06 client.py
-rw-r--r-- 1 sundar users 467 Jul  9 19:04 server.py
-rw-r--r-- 1 sundar users 957 Jul  9 19:12 weather_client.py
-rw-r--r-- 1 sundar users 785 Jul  9 19:27 weather_server.py
```

## Bash with syntax highlighting
```bash
alias c=clear
alias l='ls -AFC'
alias ll='ls -AFCl --time-style="+%Y-%b-%d %H:%M:%S"'
alias rm='rm -i'
alias mv='mv -i'
alias cp='cp -i'
alias ping='ping -i 0.2 -n'
```
## Syslog messages
```log
2016-07-09T16:53:19.085661-07:00 smaug kernel: [   16.727105] init: smbd main process ended, respawning
2016-07-09T16:53:19.165656-07:00 smaug kernel: [   16.805907] systemd-udevd[1160]: renamed network interface rename4 to eth3
2016-07-09T16:53:23.089648-07:00 smaug kernel: [   20.729693] init: failsafe main process (1971) killed by TERM signal
2016-07-09T16:53:23.128175-07:00 smaug polkitd[2636]: started daemon version 0.105 using authority implementation `local' version `0.105'
2016-07-09T16:53:33.629647-07:00 smaug kernel: [   31.268237] init: plymouth-stop pre-start process (6893) terminated with status 1
2016-07-09T16:53:35.529716-07:00 smaug udisksd[7321]: udisks daemon version 2.1.3 starting
2016-07-09T16:53:35.630875-07:00 smaug udisksd[7321]: Acquired the name org.freedesktop.UDisks2 on the system message bus
```


# Normal links
1. [Basic writing and formatting syntax] (https://help.github.com/articles/basic-writing-and-formatting-syntax/#links)
2. [Daring Fireball's markdown syntax] (https://daringfireball.net/projects/markdown/syntax#backslash)
3. [Mastering Markdown] (https://guides.github.com/features/mastering-markdown/)


A different way of using reference-style links. The links in this paragraph are REFERENCES to links in the UNTITLED section below. This is a reference to [Basic writing][1], while [this][2] is a reference to Daring Fireball's article. [This is a link to 3. Mastering Markdown][3].

## Emojis
* :elephant:

[//]: # (List of links. This line is a comment, but the remaining are required for references to work)
[//]: # (===============================================================================================)
[1]: https://help.github.com/articles/basic-writing-and-formatting-syntax/#links (Basic writing and formatting syntax)  
[2]: https://daringfireball.net/projects/markdown/syntax#backslash (Daring Fireball's markdown syntax)  
[3]: https://guides.github.com/features/mastering-markdown/ (Mastering Markdown)  




