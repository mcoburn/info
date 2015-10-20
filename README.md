account-info
============

The Fresh Diet account information

FILE
finance.asc 		Michael,Matt,Andy

accounts.asc		Fabian,Orlando,Andy,Michael

masteraccounts.asc	Fabian,Michael

miscaccounts.asc	Fabian,Orlando,Andy,Michael

marketing.asc		Rossie,Michael

opts			Options File  
				group sysadmins = System Administrators (AB,FR,MC,OS) 
				group figuys = (AB,MH,MC)
				group master = (FR,MC)
				group market = (RS,MC)
keys			Directory of Public Keys

README.md		This File

Encrypt 

gpg --options ./opts --always-trust -ear "GROUP NAME" ./File to encrypt
