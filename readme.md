#Social Player
View available BBC iPlayer programmes based on your Facebook likes 

## Install Node dependencies:
```
npm install
```

## Start the server:
```
npm start
```

##Connect database:
In a new terminal window, run:

```
mongod --dbpath /Users/yourusername/yourpathto/.../social-player/data
```

##Import JSON seed data
In another teminal window, run:

```
mongoimport -d social-player -c programmelist --file data/programmes.json
```

And then run:

```
mongo
```

```
use social-player
```

## Run
Run the programme from [http://localhost:3000](http://localhost:3000)

On clicking the 'Find programmes' button the app will connect to your Facebook account. This app is not approved by Facebook but user data is not saved.