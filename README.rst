######################
Deploying pygotham.org
######################

The enclosed playbook can be used to deploy pygotham.org.

Setup
#####

.. code::

    $ pip install -r requirements.txt
    $ ansible-galaxy install -r galaxy-requirements.txt

Usage
#####

.. code::

    $ ansible-playbook -i inventory --ask-vault-pass -e env=production playbook.yml
