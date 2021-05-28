# CVN Tech blog

## Installation
This repo is tested on **Node v12.20.1**.  While earlier versions of nodejs may be compatible, they have not been tested or verified.

### 1. Install required Software

- JDK 1.8+
- NodeJS: https://nodejs.org/en/ (version is equal or greater than v12.20.1)

### 2. Install packages

1. Open Terminal and `cd` to `code-samples-e2e` repository.
2. `cd`  to folder `setup-selenium-grid`  
3. Run the command `npm install` to install dependencies packages<br/>
4. That's all.
   
### 3. Start Selenium GRID by docker

Please follow README.md in folder `tools/docker/selenium` to start Selenium GRID by docker   


## How to run tests

Firstly, opening a terminal and `cd` to `setup-selenium-grid` folder, then execute the below command:

``` 
npm test
```