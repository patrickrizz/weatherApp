Weather App

create model
node_modules/.bin/sequelize model:generate --name Contact --attributes firstName:string,lastName:string,phone:string,email:string

migrations
node_modules/.bin/sequelize db:migrate
