**NOTE: I am not currently soliciting feedback. If you stumble upon this material, I ask that you keep your notes and comments to yourself until I remove this note. At that time I will be actively soliciting feedback as well as requesting a number of reviews. As this is course development and not simply documentation, I need time and space to work through my own creative process. Thank you for your understanding.**

# Index
Welcome to the Nubis training documentation. As of this writing this is very much a work in progress. The table of contents is currently designed to help me to design the course content and help me keep track of my progress and what I have left to accomplish. This list will eventually link out to the content covered by each section.

## Table of Contents
This Section contains the material we will cover in the classroom session. Eventually we hope to develop this into a self-guided training course that a person can work through at their own pace.

0. Introduction (Not nubis introduction, just training day intro)
  - Go right into challenges in the current working processes
  - Lay out the necessity of making a change and the need for new operating methodologies
 - Brief introduction into Nubis (no details here, just saying we made this thing and we are going to talk about it today)
~ break time ~
0. New operating principles (Best practices when working in the cloud)
 - New way of thinking (new working methodologies)
 - Twelve Factor Review
 - Symantic versioning
 - scrum
 - git & github (Specific to how we are using it) (Intended to be a review only)
 - puppet-masterless
 - puppet upgrades
 - autoscaling
 - ssh restrictions
 - security
0. Exercise One
 - Creating understanding
0. Nubis overview
 - What is Nubis?
 - What can Nubis do for me?
 - What does Nubis provide?
0. Exercise Two
 - Using Nubis to solve challenges
0. Demonstrations
 - Account Upgrade
 - Update an application AMI
 - Application Deployment
 - Troubleshooting
0. Working Labs
 - How do I set up my environment?
 - Deploying the Nubis example application (Dpaste)
 - Deploying your own application using nubis-skel

## Operational Documentation (HOWTOs)
Here are some links to context relevant HOWTOs which are intended to guide you through many of the tasks you will need to perform using Nubis.

 - How do I deploy an app
 - How do I login to AWS?
  - aws-vault overview (still might like a wrapper script for account setup)
 - Walk-through dpaste deploy
 - Build custom app with nubis-skel
 - How do I build an AMI?
  - Features of nubis-base
   - /etc/nubis.d/*
   - consul integration
  - Puppet masterless
   - Puppet modules
   - librarian-puppet
  - Packer overview
  - nubis-builder overview
   - distrobutions supported
   - project.json file requirements and options
 - How do I launch a jumphost?
 - How do I access instances
 - What is the meaning of immutable
 - What happens when my instance is marked as tainted?
 - How does monitoring work in AWS?
 - How do I upgrade my account to Nubis latest?
 - Terraform overview
 - Consul overview
 - Fluent overview
 - Proxy overview (including nat)
 - Database admin node
 - How do I add and remove users from my account
  - Levels of user permissions

## Technical Documents (Design docs)
In this section you will find links to some of our technical and design documentation. This material is intended to help you with troubleshooting. It is also helpfull if you would like to get into helping us with Nubis development.

 - NSM monitoring
 - IP Blocklist
 - Nat setup / HA / State
 - User Management
