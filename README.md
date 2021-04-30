
## Overview

This source used to pull the contract from the Pact Broker and makes the request to the localhost along with the details from the contract. And then Pact verifies the request made to the API server and returns the expected body.

## Install

- Install java sdk version 8: https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html
- Install IntelliJ: https://www.jetbrains.com/idea/download/
- Install Gradle 6.8: https://gradle.org/install/

## How to work?
- Clone source from this repo to your PC
- Go to folder that store this souce code, open terminal and run "grade pactVerify"

After verify contract, if result is correct, you will see column 'Last Verified' is green:
![image](https://user-images.githubusercontent.com/17809726/116720330-3fb0a900-aa06-11eb-97e9-929f4260cfa9.png)

If result is fail, you will see column 'Last Verified' is pink
![image](https://user-images.githubusercontent.com/17809726/116721199-3ffd7400-aa07-11eb-96b0-90d73b93c717.png)
