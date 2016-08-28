# docker-firebase

## Purpose

This image was created specifically for usage with continuous integration systems, and contains the minimum requirements to deploy a project to [Firebase](https://firebase.google.com/). Currently being used with [wercker](https://app.wercker.com), but should meet the requirements for most CI systems.

## Details

### Base Image

* [node](https://hub.docker.com/_/node/) -  Latest version of Node

### Additional Node Modules

* [Firebase CLI](https://github.com/firebase/firebase-tools) - Firebase Command Line Tools. Required to deploy to Firebase.
