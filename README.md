# Yarn Installation

## Table of Contents
- Install and Update Yarn
  - *[On Linux](#on-linux)*
  - *[On Windows](#on-windows)*


<a name="on-linux"></a>
### On Linux
1. Update package list
    ```
    sudo apt update
    ```

2. Install dependencies
    ```
    sudo apt install curl software-properties-common
    ```

3. Add Yarn repository
    ```
    curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo gpg --dearmor -o /usr/share/keyrings/yarn-archive-keyring.gpg

    echo "deb [signed-by=/usr/share/keyrings/yarn-archive-keyring.gpg] https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list > /dev/null

    ```
4. Update package list again
    ```
    sudo apt update
    ```
5. Install Yarn
    ```
    sudo apt install yarn
    ```

<a name="on-windows"></a>
### **On Windows**

1. Install yarn
   ```markdown
   npm install -g yarn
2. Update yarn

    ```
    yarn set version latest
    ```

3. Check Yarn Version
    ```
    yarn --version
    ```


