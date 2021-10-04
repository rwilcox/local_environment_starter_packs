This repository is a set of local development starter kits for various languages / frameworks.

The idea here is that regardless of technology etc used that there's a common interface over local developer use. In this way a developer can transition from a Node app to a Rails app to a Java app and have familar (idential?) tools for running the local environment.

# Using

  1. Use the scripts to start and ssh into the appropriate environment.
  2. ideally use some kind of project generator (start.spring.io? `rails new`? to generate your project setup)
  3. Place the contents of the folder _inside_ the generated project setup (ie `dev-scripts`, `docker`, `docker-compose-devel.yml`), so you have a self contained developer setup
  4. Commit to the project repository.

These scripts are provided in a boilerplate manner, as the contents may need to be modified per project (but keep the same interface!)
