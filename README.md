# MEVNF-boilerplate
A fullstack boilerplate with Mongo, ExpressJS, VueJS, NodeJS and Foundation-Sites.

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSOOiKh1Xk5RDZFKPkVXYfi8U-t2cuotiAOR7G_7w_HWXfV02TMnd9wnVM" height="50" /> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://i.cloudup.com/zfY6lL7eFa-3000x3000.png" height="50" /> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="/docs/Vue.js_Logo.svg.png" height="50" />  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://upload.wikimedia.org/wikipedia/commons/7/7e/Node.js_logo_2015.svg" height="50" />  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://zurb-dot-com-prod.s3.amazonaws.com/asset/665/raw_2Fef82d607-243f-4eda-922c-f1e42ddf7a39_2FFoundation-for-Sites.png" height="50" />

A skeleton generated with MEVN stack technologies which can be used as a boilerplate for anyone who is starting out. It contains a client template(**VueJS**) and a server template(**NodeJS**, **ExpressJS**) and a connection between them via an API layer. It also includes a SASS compiler and Foundation-Sites SASS Library for a semantic, readable, flexible, responsive and completely customizable UI framework.


## Setup Development Machine
1. Clone the repo

2. `cd MEVNF-Boilerplate`

3. Install Dependencies
```
npm install -g vue-cli nodemon
npm install
```

4. Start local MongoDB (or connect to remote instance - instruction below)
https://docs.mongodb.com/manual/tutorial/getting-started/


5. Start Express Server
```
npm run server
```

6. Run Application
```
npm run dev
```

7. Open `http://localhost:8080` in browser


## Additional build tasks
##### build for production with minification
```
npm run build
```

##### build for production and view the bundle analyzer report
```
npm run build --report
```

##### run unit tests
```
npm run unit
```

##### run e2e tests
```
npm run e2e
```

##### run all tests
```
npm test
```


## Remote MongoDB Connection
To connect to a remote MongoDB instance update the url in `server/server.js` with your connection string provided by your remote settings:
```
const uri = "mongodb://localhost:27017/posts";
mongoose.connect(uri);
```

This Boilerplate was constructed following the instructions outlined in [Build full stack web apps with MEVN Stack](https://medium.com/@anaida07/mevn-stack-application-part-1-3a27b61dcae0)

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
