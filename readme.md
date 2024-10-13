 
## Commandos

### Criação do projeto
Instalar projeto inicial
```
yarn init -y
```
```
yarn add express
```
```
yarn add nodemon sucrase -D
```
#### Para iniciar
```
yarn dev
```
### Banco ORM
Installar
```
yarn add sequelize
```
```
yarn add sequelize-cli -D
```
```
yarn add pg pg-hstore
```
Criar migração
```
yarn sequelize migration:create --name=create-users
```
Rodar a migração
```
yarn sequelize db:migrate
```
Desfazer uma migração
```
yarn sequelize db:migrate:undo
```
Desfazer todas as migração
```
yarn sequelize db:migrate:undo:all
```