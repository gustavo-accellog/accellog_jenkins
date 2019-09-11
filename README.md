# Accellog Jenkins Project

## Objetivo

Subir uma máquina com Jenkins para atualizar os projetos em Java, PHP e Vue.JS da empresa.

## Java Spring Boot

* Criar Dockerfile para o projeto (na raíz do repositório).
* Criar Jenkinsfile para o projeto (na raíz do repositório).
* Criar Job no Jenkins com Pipeline que lê o Jenkinsfile (Criar Docker com Maven e faz build do projeto).