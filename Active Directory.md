---
share: "true"
---

```table-of-contents
```
# Organisatorisches
## Präsi: AD goes cloud - ??
- 5.7.
- 1h-offen
- sachen zeigen
- git repo für obsi
- 1 zwischen präsi
- wenn name da -> eintragen
## Ziel
- AzureAD verstehen
- on-prem grob verstehen
	- aufbau
	- was sind gpo
	- was sind ou's
	- was ist ein sinnvoller aufbau
- Das zum laufen bringen
- einen use-case testen
	- bsp. win10 mit passwort policy, hintergrund, restristed access
	- applikationen mit gpo anpassen
		- url zu verfügung stellen
		- browser einstellen
- externes services anbinden
- identity access management
	- SAML und so
	=> ggf. in präsi
## Sachen
- Namenkonventionen
- keine zahlen bei server namen am anfang
## Objekte
- Benutzer
	- admins extra
- Gruppen
	- lokal
	- global
	- universal (das hier nehmen)
	- gruppentyp
		- sicherheit
		- verteilung -> exchange
	- https://en.wikipedia.org/wiki/AGDLP
- Geräte
## Wie PC in AD aufnehmen
systemeigenschaften -> computer -> namen ändern -> name eintragen
## Ziele
### 13.06.2024
- Entra einbinden
- was wird gebraucht?
- geht das so? oder brauchen wir einen paid service
	=> geht auf jeden fall mit sva mail nicht
- ~~core -> gui~~ neuinstallation zusätzlich
- AzureAD Connect wie?
- [x] git repo zugänglich machen
## Ausblick
- Fileshare, Home-Laufwerke und Benutzerprofile
## Dokumentation
### 12.06.2024
- https://woshub.com/windows-server-core-install-active-directory-domain-controller/
- ~~`Install-ADDSDomainController` in PS wenn GUI nicht zur Verfügung steht~~ geht nicht
- [x] RoyalTS setup
- [x] 2 Windows Server mit GUI installieren