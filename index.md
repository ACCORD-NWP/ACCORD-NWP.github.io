ACCORD Forge documentation
==========================

*everything remains to be written here...*

Join the organisation
---------------------

0. Create your github professional account if you don't have one. (Please use your official professional e-mail address)
1. Contact the ACCORD System Area Leader, asking for being a member of the ACCORD forge, and providing your github identifier.
2. He will send you an invitation, that you finally just have to accept.

Configure your settings for a smooth Git connexion
--------------------------------------------------

* go to your account _Settings_ > _Developer settings_ > _Personal access tokens_
* _Generate new token_
  (setting "repo" as scope, and with a reasonable expiry date)
* set this token in any host .netrc file:
  `machine github.com login <your github userid> password <the generated token>`
* in case you organisation is using a proxy, you need to tell Git to use it: e.g. 
  `export GIT_SSL_CAINFO=/usr/local/etc/proxy1.pem` in MF/CNRM
