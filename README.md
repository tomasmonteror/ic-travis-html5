# Integración continúa: Comprobación de html5 válido y Despliegue en surge.sh 

[![Build Status](https://travis-ci.org/josedom24/ic-travis-html5.svg?branch=master)](https://travis-ci.org/josedom24/ic-travis-html5)


Integración continua con Travis que realiza dos operaciones:

* test: Comprueba que el HTML5 es válido. Para ello vamos a utilizar (https://github.com/svenkreiss/html5validator)
* deploy: Si la prueba ha sido exitosa se sube al servicio surge.sh (http://surge.sh/)


