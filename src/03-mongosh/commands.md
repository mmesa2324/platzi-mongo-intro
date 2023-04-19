## Connect to container

'''sh
docker-compose exec mongodb bash
'''

## Connect with mongosh

'''sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://mesalops:Migue2324@mongodb01.69msz26.mongodb.net/test"
'''

'''sh
show dbs
show collections 
'''

'''sh
use use("platzi_store")
db.products.find()
'''