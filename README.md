# lpunpack & lpmake precompiled binaries!
A tool to unpack android super.img [RAW img's only]!

## What is this?
lpunpack & lpmake is originally made by [LonelyFool](https://github.com/LonelyFool) and the OG github page can be found [here](https://github.com/LonelyFool/lpunpack_and_lpmake)!

## How to install it?

1. Clone this repo.

`git clone https://github.com/Exynos-nigg/lpunpack-lpmake-mirror.git lpbinary`


2. Cd to work dir.

`cd lpbinary`


3. Execute bash script.

`bash install.sh`

if it errors out, try running sudo su before this command =)


4. Done!

## How to use it?

`lpunpack --slot=0 <path to ur raw system.img> <ur output folder>`  |  This will unpack slot A images

`lpunpack --slot=1 <path to ur raw system.img> <ur output folder>`  |  This will unpack slot B images

NOTE : Make sure ur output folder already exists before executing the above command!

## Credits

 - Me, for compiling it and making a bash script and writing a readme lmao
 - [LonelyFool](https://github.com/LonelyFool), for his OG tool

