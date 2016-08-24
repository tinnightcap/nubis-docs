# Nubis Overview
The nubis project provides several things which are closely integrated.
 - Nubis accounts
 - Nubis deployments
While it is not necessary to use Nubis Deployments you must be using a Nubis Account in order to take advantage of Nubis Deployments. We highly recommend using Nubis Deployments on top of a Nubis Account as it provide many advantages over developing individual deployment methods.

## Nubis Accounts
Nubis accounts contain all of the basic services that one would expect to find in a datacenter such as monitoring and integration into security systems. The account services are updated and maintained by the Nubis development team. We take care of system upgrades as well as ensuring the services run correctly and integrate with each other. There are a large number of security requirements that are satisfied when deploying a Nubis account.

The Nubis development team releases a new version of Nubis accounts quarterly. it is the responsibility of the account owner to upgrade their accounts to the latest Nubis accounts within one quarter following a release. The Nubis development team works very diligently to ensure this upgrade is a seamless as possible. There is a very simple process to upgrade an account, consisting primarily of a single Terraform command.

TOTO: links & demos.

## Nubis Deployments
Nubis Deployments consist of a collection of modules and recommended practices that streamline application deployments into a Nubis Account. The Nubis Deployment components tightly integrate with Nubis Accounts and help to ensure consistency, ease of release and security compliance. Additionally they provide a turn key CI system that automate application builds, deployment to a staging environment and automated testing. All that is left is to push a button to deploy the application into production. This enables rapid development as well as least-privileged access for getting applications into production.