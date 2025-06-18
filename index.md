
![logo](https://github.com/user-attachments/assets/b12da2cd-f3aa-4197-933c-1969724f96fd)

ACCORD Forge documentation
==========================

*everything remains to be written here...*

Repositories documentation
--------------------------
* [DAVAÏ Users Guide](https://accord-nwp.github.io/DAVAI-env/stable/) DAVAI environment for testing experiment creation
* [DAVAÏ ](https://accord-nwp.github.io/DAVAI/stable/) DAVAI merged repo
* [DAVAÏ-ciboulai ](https://accord-nwp.github.io/DAVAI-ciboulai/stable/) Ciboulai : the interactive dashboard for DAVAï
* [DAVAÏ-test ](https://accord-nwp.github.io/DAVAI-test/stable/) DAVAI tests templates and config files
* [IAL-build ](https://accord-nwp.github.io/IAL-build/stable/) Wrappers to help building IAL executables from SCM
* [IAL-expertise](https://accord-nwp.github.io/IAL-expertise/dev/) IAL outputs expertise toolbox
* [ACCORD_documentation](https://accord-nwp.github.io/ACCORD_documentation/dev/) Repository for markdown ACCORD documentation
* [ACCORD Preprocessing Tools](https://accord-nwp.github.io/AccordPreprocTools/dev/) Gathering various existing observations preprocessing tools and document them
* [ACCORD DA TOOLS](https://accord-nwp.github.io/AccordDaTools/dev/) ACCORD Data Assimilation Tools
* [ACCORD Physics Tools](https://accord-nwp.github.io/ACCORDPhysicsTools/dev/) ACCORD Physics evaluation and validation tools
* [PHYEX](https://accord-nwp.github.io/PHYEX/dev/) PHYsique EXternalisée
* [EPyGrAM](https://accord-nwp.github.io/EPyGrAM/dev/) Enhanced Python for Graphics and Analysis of Meteorological fields
* [Fick](https://accord-nwp.github.io/Fick/dev/) A Fortran toolkit for interoperating Fortran with C/C++
* [Eckit](https://accord-nwp.github.io/Eckit/dev/) A C++ toolkit that supports development of tools and applications at ECMWF
* [field_api](https://accord-nwp.github.io/field_api/dev/) Field API aims to ease the management and the transfer of data between CPUs and GPUs for the IFS-ARPEGE-LAM software.
* [Tallinn_GitHub_TestRepo](https://accord-nwp.github.io/Tallinn_GitHub_TestRepo/dev/) Test repository for Tallinn Surface side meeting with GitHub exercise
* [ectrans](https://accord-nwp.github.io/ectrans/dev/) Global spherical harmonics transforms library underpinning the IFS
* [ecsaber](https://accord-nwp.github.io/ecsaber/dev/) 
* [Fiat](https://accord-nwp.github.io/Fiat/dev/) The fortran IFS and ARPEGE Toolkit
  

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
