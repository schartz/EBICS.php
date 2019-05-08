EBICS
=============

Fork of [Synap/EBICS.php](https://github.com/Synap/EBICS.php)


A PHP library project for the EBICS protocol (French version)

EBICS is THE standard of the moment for everything related to the automation of bank exchanges. However, as this protocol is still young, there are few free licensed libraries. In addition, some variants exist between French banks and German banks.

This project aims to develop a PHP library compatible with French banks in order to offer developers an easily exploitable software component for their accounting, e-commerce, or other management applications projects ...

The purpose of Synap System is to encourage and assist the development of free software. As a result, the license for this project is GNU Affero General Public.

A fee-based dual license system for companies that would find the GNU Affero General Public license too restrictive is also being considered. Contact us if you are interested.

Due to lack of funding, no release date is planned for the moment and the development is done over the water.

If you wish to help us financially, if you have a suggestion or wish to contribute, you can send an e-mail to the following address: contact@synap.fr or on gitter.im


Installation
============

Ce projet nécessite [composer](https://getcomposer.org/) pour l'installation des dépendances:

    git clone https://github.com/Synap/EBICS.php.git
    cd EBICS.php
    composer install

Once this is done, copy the `parameters.json-dist` file to an parameters.json file and edit it to insert the EBICS server connection parameters.

- `test/fixtures/keys/A005/cert.pem`
- `test/fixtures/keys/A005/key.pem`
- `test/fixtures/keys/E002/cert.pem`
- `test/fixtures/keys/E002/key.pem`
- `test/fixtures/keys/X002/cert.pem`
- `test/fixtures/keys/X002/key.pem`

You can then test the following commands:

- `app/console ebics:hev`
- `app/console ebics:hia`
- `app/console ebics:ini`

Warning! This project is under development. Use these commands only for testing purposes and at your own risk.

Liens
=====

- [ebics.org](http://www.ebics.org/)
- [Service gratuit de test](https://software.elcimai.com/efs/accueil-qualif.jsp)
- [Epics (bibliothèque en ruby)](https://github.com/railslove/epics)
- [Module EBICS pour OpenConcerto (JAVA)](https://code.google.com/p/openconcerto/source/browse/trunk/Modules/Module+EBICS/)
- [Un autre client EBICS en Java](http://sourceforge.net/projects/ebics/)
- [An Introduction to
XML Signature and XML Encryption
with XMLSec](http://users.dcc.uchile.cl/~pcamacho/tutorial/web/xmlsec/xmlsec.html)

