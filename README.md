
### ✅ Prerequisites  
Ensure you have the following installed on your system:  
- **[Node.js](https://nodejs.org/)** (LTS version recommended)  
- **npm** (Comes with Node.js)  
### install node js 
```
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt install -y nodejs
```
### install pm2 for daemon service running on server  
```
npm install -g pm2
pm2 start server.js --name grocery-backend
pm2 save
pm2 startup
```

npm init -y
npm install express mongoose cors 
node server.js


### run following command on mongodb view your data
```
mongosh
use grocerydb
db.groceries.find()
```
