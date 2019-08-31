# VidChat

* Author: Arthur Kalikiti
* Date: 20 February, 2019


This is a one to one video chatting application written in javascript running on a nodejs backend.

**NOTE**: This application only runs on HTTPS, as the use of HTTP with WebRTC is deprecated in most modern browsers.
Be certain to setup a self signed certificate for development purposes, and use LetsEncrypt free certificate in production (Any CA is applicable though).
# SETUP

1. Start by installing NodeJS
    
    ### CentOS (RHEL)
    
    ```bash
    sudo yum install nodejs
    ```

    ### Ubuntu (Debian)

    ```bash
    sudo apt install nodejs
    ```
2. Then install npm 

    ### CentOS (RHEL)

    ```bash
    sudo yum install npm
    ```

    ### Ubuntu (Debian)

    ```bash
    sudo apt install npm
    ```

3. The app uses varibale in the .env file, to create one from the sample, execute:

    ```bash
    cp .env.example .env
    ```

4. Now you need to get app dependencies using npm.

    ```bash
    npm install
    ```

    >The above command downloads all dependecies in the [package.json](package.json) file.

5. Now you are ready to run the app. Execute:

    ```bash
    npm start
    ```

## LICENSE

This is an open source project released under the [MIT licence](LICENSE.md), meaning anyone with ac
cess to this code can literally do whatever pleases them with the code.
The author of this source code, does not in any way assume any lose and/or damage that may arise from the use or acquisition of this software.

Happy Coding :joy: