# Experiência 1 2
## Getting smaller...
### And smaller...
#### Even smaller...

![Image of Zelda in Echoes of Wisdom](https://images.nintendolife.com/aa2693b38e42a/echoes-of-wisdom.large.jpg)

``` javascript

/*Connect databse*/

const {MongoClient} = require('mongodb');
require('dotenv').config();
const url = process.env.SERVER_LOCAL_LUIS;
const client = new MongoClient(url);


const dbname = "Family"
const collname = "pets"
const pets_coll = client.db (dbname).collection (collname)
const doc_tobias = {"petid":160, "name":"Tobias", "age":4, "gender":'Male'};

```

Afazeres
- [x] List syntax is required
- [x] This item is complete
- [ ] This item is not complete
