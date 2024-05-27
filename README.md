# <h1 align="center">RISC-Zero Trusted Setup Ceremony</h1>
![image](https://github.com/UnicorNn1/RISC-Zero/assets/82544940/f26e9057-f29e-4db9-9373-4033bae39eb1)


## Links:
 * [RISC-Zero Official Website](https://www.risczero.com/)
 * [RISC-Zero Official Twitter](https://twitter.com/risczero)
 * [RISC-ZeroOfficial Discord](https://discord.com/invite/risczero)
 * [RISC-Zero Documentation](https://dev.risczero.com/api)

### System Requirements
| System | Minimum Requirements | 
| ------------ | ------------ |
| ✔️RAM	| 8 GB |
| ✔️Bandwidth| 25 Mbps |
## GitHub Account Requirements:
You must have at least 1 publicly accessible repository.
You must be following at least 5 GitHub users.
You must have at least 1 follower.

## Installation:
Setup Dependencies and Install Binaries:
```
curl -sL https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.0/install.sh | sh -
source ~/.profile
mkdir p0tion-tmp
cd p0tion-tmp
nvm install 16.20
nvm use 16.20
npm install @p0tion/phase2cli
```
## Verify GitHub Account
Note: When you enter the code, it will give you a code on the page. you will go to this link and paste that code. https://github.com/login/device
```
npx phase2cli auth
```
## Contribution
Since this step is an interactive shell and cannot be run in the background, screen will be used during the process.
```
screen -S risczero
```
```
npx phase2cli contribute
```
## Follow the instructions and continue until you see the message "You must wait for xxx participants (~xx:xx:xx:xx:00 (dd/dd/dd/ss))".
To close the screen, hold down the CTRL key and press the A key and then the D key.
To check your progress
```
 screen -r risczero 
```
## run the following code when the operations are completed successfully
```
npx phase2cli clean
```
