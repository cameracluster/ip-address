# ip-address
- a simple shell script that shows user's IP address info
- ip-address uses the API from https://ipapi.com to request a json object of user's IP info and returns a minimal output of the user's country of origin, city, continent and ip address.

## Screenshot:
![screencap](https://github.com/cameracluster/ipapi-shell/blob/main/scap2.png?raw=true)

## Required:
1. An API access key from https://ipapi.com (Free)
2. [cURL](https://curl.se/)
3. [jq](https://jqlang.github.io/jq/)

## Usage:
1. clone this repo with:
```
git clone https://github.com/cameracluster/ip-address.git
```
2. Paste API access key into ip-address.sh under `access_key=...`
3. Envoke ip-address by running in your shell of choice:
```
./ip-address.sh
```
