# vuejs heroku example
 is a simple example of vuejs running on heroku




https://medium.com/netscape/deploying-a-vue-js-2-x-app-to-heroku-in-5-steps-tutorial-a69845ace489


npm install --global vue-cli


Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope LocalMachine

vue init webpack vuejs_heroku_example

cd vuejs_heroku_example

npm install

npm run dev



#Heroku

https://devcenter.heroku.com/articles/heroku-cli#download-and-install

heroku create vuejsherokuexample 

heroku config:set NODE_ENV=production --app vuejsherokuexample




npm run build