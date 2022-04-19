# gha-testing
Github actions + Terminus commands + drush

This is a simple workflow that will get terminus, authenticate and run a 
drush command on an environment.

Based on:

https://github.com/twfahey1/terminus-gh-actions
https://github.com/kopepasah/setup-pantheon-terminus

Requires the following secrets be setup:

* PANTHEON_MACHINE_TOKEN - generated on pantheon 
* PANTHEON_SSH_KEY - private key stored on github and public key stored on Pantheon

