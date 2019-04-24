# tn-register-multiple-account
Tools for register multiple account in website https://trangnguyen.edu.vn

## Install package dependencies npm

`npm i`

## Run

### Create want enter captcha:

`npm start`

Or set number account you want creat, example create 100k users

`NUMBER_USER=100000 npm start`

### Create no need enter captcha:

`npm run no-captcha`

Or create user and save log:

`NUMBER_USER=100000 npm run no-captcha > users.log`

Or append to file log (recommend):

`NUMBER_USER=100000 npm run no-captcha >> users.log`

### Create user forever:

`npm run forever`

Or create user and save log:

`npm run forever > forever.log`

Or append to file log (recommend):

`npm run forever >> forever.log`

## Enter captcha

Please enter captcha at the console show screen

!['Screenshot](https://github.com/viet-tools/tn-register-multiple-account/blob/master/Screenshot.png?raw=true)

Enjoy!