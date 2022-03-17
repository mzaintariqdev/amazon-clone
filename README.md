# Installation Steps

## Using npm

Run commands

1. `npm install`

2. `npm run dev`

## Or using yarn

Run commands

1. `npm install --global yarn`

2. `yarn install`

3. `yarn run dev`

### If you see the window below then you are set to build AMAZON 2.0!

![Template Screenshot](TemplateScreenshot.jpg?raw=true 'Template Screenshot')

# Authentication

before that we have to go gcp console to use nextauth we need to add uri for our project were we need to select our project for which we are going to auth this is the project we have on firebase console

to add uri go to API and services ->credentials->add consent screen if not already done after that go to credentials ->create credentials->oauth client id ->application type -> web application add uri -> create by this you will get client id and secret id which can also get
From web sdk configuration of google firebase authentication
write these in env.local file
GOOGLE_ID= goes here

GOOGLE_SECRET= goes here
NEXTAUTH_URL=http://localhost:3000
