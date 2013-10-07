TestBundle
===========

Solo para probar el bundle de symfony adiciona de momento una vista de banner la que no es configurable "solo tiene un link a google.com"


INSTALL
=======

1) Installing the Standard Edition
----------------------------------

use composer to install the TestBundle

    php composer.phar require "gaston/test-bundle":"dev-master"

2) Configuration
-----

Modify 'App.kernel.php' to add this line

    new Gaston\TestBundle\GastonTestBundle(),

3) Apply the view
------------------

In some view only add this line

    {{ include('GastonTestBundle:Banner:index.html.twig') }}