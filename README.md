# YE OLDE REPO README

I'll put together a better readme later(maybe) but for now this is what you get.

This repo contains two subdirectories with distinct but complementatry projects, golang-openapi-service and cloudformation-gitops-repo.

golang-openapi-service : this repo is eventually going to contain a RESTful api implementing openapi and generated with go-swagger, it will be containerized using a dockerfile and hosted as a node on an ECS instance. 

    I'll probably create other microservices to expose through golang-openapi-service 

cloudformation-gitops-repos : this repo will contain the cloud formation template files for provisioning and managing the deployment of golang-openapi-service and potentially other containerized services on an instance of ecs


