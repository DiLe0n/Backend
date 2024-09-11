Basic server in .js using xampp and mysql

1.- Download xampp and node.js in the following links
  nodejs.org
  apachefriends.org

2.- In new terminal use this command
  npm install express sequelize mysql2

3.- Open xampp and run Apache and MySQL, next run the server with
  node servidor.js

4.- Try it with this commands
  http://localhost:3000/users?action=create&nombre=John&usuario=jdoe&contrasena=123456

  http://localhost:3000/users?action=read

  http://localhost:3000/users?action=read&id=1

  http://localhost:3000/users?action=update&id=1&nombre=Jane&usuario=jdoe2&contrasena=654321

  http://localhost:3000/users?action=delete&id=1
