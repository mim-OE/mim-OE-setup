# mimOE-Setup Shell Script

## Description

mimOE is available in 2 versions:

1. mimOE

   - Standard version and is recommended for use in non AI applications and solutions.

2. mimOE-ai
   - This version is AI enabled and is recommended for use in AI applications and solutions

Follow instructions below to install mimOE or mimOE-ai using shell script.

⚠️ **Shell scripts can only be used on below operating systems** ⚠️

1. Apple macOS
2. Linux(amd64 and arm64)

## install mimOE or mimOE-ai using shell script.

1.  Go to [Releases](https://github.com/mimik-mimOE/mimOE-setup/releases "mimOE install shell script download page")
2.  Under <font color="green">Latest</font> click on:
    - "install-mimOE.sh" if you want standard version
    - "install-mimOE-ai.sh" if you want AI enabled version
3.  This will download shell script on to your computer
4.  Open terminal window and navigate to where you saved the shell script
5.  Give the shell script execution rights. **Be sure to use the correct file name**
    ```shell
    chmod a+x install-mimOE.sh
    ```
6.  Run the shell script
    ```shell
    ./install-mimOE.sh
    ```
7.  You should see mimOE start logs similar to below
    ```log
    Downloading mimOE-SE-macOS-developer-arm-v3.12.0.zip...
    % Total % Received % Xferd Average Speed Time Time Time Current
    Dload Upload Total Spent Left Speed
    0 0 0 0 0 0 0 0 --:--:-- --:--:-- --:--:-- 0
    100 7921k 100 7921k 0 0 8037k 0 --:--:-- --:--:-- --:--:-- 8037k
    Archive: mimOE-SE-macOS-developer-arm-v3.12.0.zip
    inflating: default.metallib
     inflating: edge
     inflating: mimikEdge.lic
     inflating: **MACOSX/.\_mimikEdge.lic
     inflating: start.sh
     inflating: **MACOSX/.\_start.sh
    start.sh found. Running it...
    [2024-09-18 11:57:02.489] [info] edge version: v3.12.0 (developer edition)
    [2024-09-18 11:57:02.489] [info] nodeName:
    Database does not exists ./.edge/.cache/.cert-db, will now create
    Opened database successfully
    Table created successfully
    [2024-09-18 11:57:02.827] [info] [initial_supernode_discovery]: starts
    [2024-09-18 11:57:04.829] [info] [initial_supernode_discovery]: supernode found:
    67d20b9e827068d996e21b3d54c7300e0d99b7065bf86a226eba1e26
    192.168.1.76
    [2024-09-18 11:57:04.829] [info] serve as supernode
    [2024-09-18 11:57:04.830] [info] serveAsSupernode
    [2024-09-18 11:57:04.831] [info] [request__mts_token] starts
    [2024-09-18 11:57:04.896] [info] [api_client_request] correlationId=b4b1c47d-0e25-a532-c497-438f970af865@0, method=POST, host=mst.mimik360.com, uri=/mST/v1/oauth/token
    [2024-09-18 11:57:04.970] [info] [api_client_response] correlationId=b4b1c47d-0e25-a532-c497-438f970af865@0, method=POST, host=mst.mimik360.com, uri=/mST/v1/oauth/token, statusCode=201
    [2024-09-18 11:57:04.971] [info] [request__mts_token] ends
    [2024-09-18 11:57:05.036] [info] [api_client_request] correlationId=2522a3a7-2c44-d02d-893f-edd7b153d5c7@0, method=POST, host=mds.mimik360.com, uri=/mDS/v1/nodes
    [2024-09-18 11:57:07.701] [info] [api_client_response] correlationId=2522a3a7-2c44-d02d-893f-edd7b153d5c7@0, method=POST, host=mds.mimik360.com, uri=/mDS/v1/nodes, statusCode=201
    [2024-09-18 11:57:07.783] [info] Tunnel (1) Established
    ```
8.  You now have mimOE runtime up and running on your machine

## Download Shell script using cURL

- Note: You may need to install cURL before running below commands

- Run command below to download "install-mimOE.sh"

```bash
curl -L -o- https://github.com/mimik-mimOE/mimOE-setup/releases/download/v3.x/install-mimOE.sh | bash
```

- Run command below to download "install-mimOE-ai.sh"

```bash
curl -L -o- https://github.com/mimik-mimOE/mimOE-setup/releases/download/v3.x/install-mimOE-ai.sh | bash
```
