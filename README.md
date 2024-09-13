After installation truffle.  
First ensure you are in a new and empty directory.

```
truffle unbox emojidao/ERC4907Box
```

If you want to create a directory, you can also run:

```
truffle unbox emojidao/ERC4907Box <Directory Name>
```

Running the unbox command should install the required dependencies.
Now, run the development console. This will spin up and allow you to interact with ganache, a local test chain on localhost:9545.

```
truffle develop
```
Compile and migrate the smart contracts. Running migrate will do both. Note inside the development console we don't have to preface commands with truffle.

```
migrate
```
In the client directory, we run the React app. Smart contract changes must be manually recompiled and migrated.


// in another terminal (i.e. not in the truffle develop prompt)
```
cd client
npm install
npm run start
```