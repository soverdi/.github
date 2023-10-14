# L'écosystème [Soverdi](https://soverdi.org/)

L'écosystème Soverdi est composé des projets et libraries suivantes:

<br>

### [soverdi-app](https://github.com/soverdi/soverdi-app) 	:iphone:
**Application PWA accessoire à la gestion de forêt urbaine**
- ReactJS
- Typescript
- Dépendances
    - [soverdi-api-models](https://github.com/soverdi/soverdi-api-models)
    - [portail-api-models](https://github.com/GOAzimut/portail-api-models)
    - [portail-api-client](https://github.com/GOAzimut/portail-api-client)
    - [gonet-messenger](https://github.com/GOAzimut/gonet-messenger)
  
| Stage | URL | Host | CI |
| --- | --- | --- | --- |
| prod | [soverdi.goazimut.com](https://soverdi.goazimut.com/) | [WWWLINUX](192.168.106.32) | GA* |
| beta | [soverdibeta.goazimut.com](https://soverdibeta.goazimut.com/) | [AZITESTLINUX-01](192.168.106.34) | GA*|

<br>

### [soverdi-api](https://github.com/soverdi/soverdi-api) :desktop_computer:
**Traitement automatique des OCTR qui sont reçus par courriel electronique**
- NodeJS
- Typescript
- Dépendances
    - [soverdi-api-models](https://github.com/soverdi/soverdi-api-models)
  
| Stage | URL | Host | CI |
| --- | --- | --- | --- |
| prod | [soverdiapi.goazimut.com](https://soverdiapi.goazimut.com/) / [doc](https://soverdiapi.goazimut.com/doc) | [WWWLINUX](192.168.106.32) | GA* |
| beta | [soverdiapibeta.goazimut.com](https://soverdiapibeta.goazimut.com/)  / [doc](https://soverdiapibeta.goazimut.com/doc) | [AZITESTLINUX-01](192.168.106.34) | GA*|

<br>

### [soverdi-api-models](https://github.com/soverdi/soverdi-api-models) (Librairie)
**Librairie partagée pour les models de l'application Soverdi**
- Typescript
- Utilisable en tant que module [npm subrepo](https://github.com/GOAzimut/.github-private/blob/main/profile/NPM_SUBREPO.md)

### [soverdi-api-client](https://github.com/soverdi/soverdi-api-client) (Librairie)
**Librairie partagée pour communiquer avec l'API de l'application Soverdi**
- Typescript
- Utilisable en tant que module [npm subrepo](https://github.com/GOAzimut/.github-private/blob/main/profile/NPM_SUBREPO.md)
- Dépendances
      - [soverdi-api-models](https://github.com/soverdi/soverdi-api-models)

<br>
<br>
*GA = Github Actions
<br>
<br>
