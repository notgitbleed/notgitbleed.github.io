layout: page
title: !GitBleed
permalink: /gitbleed/

# !GitBleed
## Issues
There are two separate but related issues that independently picked the name GitBleed; the second of these to be published has 
renamed to NotGitBleed. 

## GitBleed – Finding Secrets in Mirrored Git Repositories – CVE-2022-24975
![GitBleed Logo](https://wwwsnightwatchcybersecuritycom.files.wordpress.com/2022/02/gitbleed_icon-3.png?w=96)
 Due to a discrepancy in Git behavior, partial parts of a source code repository are visible when making copies 
 via the “git clone” command. There are additional parts of the repository that only become visible when using 
 the “–mirror” option. This can lead to secrets being exposed via git repositories when not removed properly, 
 and a false sense of security when repositories are scanned for secrets against a cloned, non-mirrored copy.
 
 For full details see the Nightwatch Cybersecurity post 
 [https://wwws.nightwatchcybersecurity.com/2022/02/11/gitbleed/](https://wwws.nightwatchcybersecurity.com/2022/02/11/gitbleed/)

## NotGitBleed - GitHub credential leakage via commit Meta-Data
<img src="https://www.notgitbleed.com/NotGitBleed2Color.svg" width="200">
Due to configuration errors or human error, significant numbers of people have accidentally checked GitHub credentials 
into GitHub commits as metadata, most commonly a username as the author name and a password in the email address field. 
It's estimated in the region of 50,000 to 100,0001 user credentials may have been affected covering a wide range of 
organisations including governments, corporations, large open-source foundations as well as smaller organisations and individuals.

For full details see the NotGitBleed post:
[https://www.notgitbleed.com/](https://www.notgitbleed.com/)
