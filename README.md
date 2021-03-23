Note: Those who are facing error in orginal git repository
1. Error: Cannot enqueue Handshake after already enqueuing a Handshake. ( comment all // connection.connect(); and // connection.end(); in passport.js
2. TypeError: Cannot read property 'insertId' of undefined ( resolve it by creating the **users** table manually in phpmyadmin using the provided code in scripts/create_Database.js)
# Complete Guide to Node Authentication with MySQL



Code for the entire scotch.io tutorial series: Complete Guide to Node Authentication with MongoDB

Current version database is ported to MySQL

We will be using Passport to authenticate users locally, 

## Instructions

If you would like to download the code and try it for yourself:

1. Clone the repo: `git clone git@github.com:manjeshpv/node-express-passport-mysql.git`
1. Install packages: `npm install`
1. Edit the database configuration: `config/database.js`
1. Create the database schema: `node scripts/create_database.js`
1. Launch: `node server.js`
1. Visit in your browser at: `http://localhost:8080`


Licence: 1
