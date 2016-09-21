# Working Labs
In this section we will be setting up our tool chain and then putting hands on keyboards. We will have the opportunity to actually use Nubis to complete a working deployment.

 - [Setting up your local environment](#setting-up-your-local-environment)
 - [Working with git & GitHub](#working-with-git--github)
 - [Deploying the Nubis example application Dpaste](#deploying-the-nubis-example-application-dpaste)
 - [Deploying your own application using nubis-skel](#deploying-your-own-application-using-nubis-skel)
 - [Updating system level packages](#updating-system-level-packages)

## Setting up your local environment
In this working lab the instructor will help the students to get their local environments set up to work with Nubis. The documentation on the process is [here](https://github.com/Nubisproject/nubis-docs/blob/master/PREREQUISITES.md).

## Working with git & GitHub
In this lab each student will clone the nubis-dpaste repository. The students will then create a feature branch, make a small change and push that back to GitHub. They will then make a pull-request back to the master branch of their fork.

**TODO** Write a document containing specific instructions (copy-paste style). Figure out what change can be made to Dpaste to personalize the deployment to each student. I am thinking updating the top-of-page text to their nic or name.

## Deploying the Nubis example application (Dpaste)
In this lab the students will be walked through deploying their application into the training account. They will use Terraform to push their locally modified Dpaste into the training environment. The documentation can be found in the [README.md](https://github.com/nubisproject/nubis-dpaste/blob/master/README.md) document.

## Deploying your own application using nubis-skel
In this lab, the students will be shown how to make use of nubis-skel to rapidly prepare a local deployment. They will add the necessary configuration to be able to deploy a single EC2 instance into the training account. Ideally they will be able to log onto the instance. If time permits the lab can be extended to add custom code, roll new images and push them into the training account as well.

**TODO** Update nubis-skel [README.md](https://github.com/nubisproject/nubis-skel/blob/master/README.md) document

**TODO** Create nubis-skel example usage document

## Updating system level packages
This lab will take an existing deployment and walk the students through updating system level packages. This is updating a package the application relies on, a library dependency.

**TODO** Create document with copy-paste instructions for updating a single library.
