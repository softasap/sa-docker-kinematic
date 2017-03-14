sa-docker-kitematic
===================

[![Build Status](https://travis-ci.org/softasap/sa-docker-kitematic.svg?branch=master)](https://travis-ci.org/softasap/sa-docker-kitematic)


Simple:

```YAML


     - {
         role: "sa-docker-kitematic"
       }

```


Advanced:

```YAML


    - {
        role: "sa-docker-kitematic"
      }

```


See box-example for standalone installation example


Usage with ansible galaxy workflow
----------------------------------

If you installed the sa-docker-kitematic  role using the command


`
   ansible-galaxy install softasap.sa-docker-kitematic
`

the role will be available in the folder library/sa-docker-kitematic

Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-docker-kitematic"
       }

```



Copyright and license
---------------------

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)
