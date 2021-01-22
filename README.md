# new-obsidian-demo

A demo app to demonstrate the features of Obsidian 2.0

To try it out: 
1. Install the latest version of Deno  
2. Install the latest version of Redis to create an instance
3. Create a .env with:
```
PG_URI=postgres://uiikgqgj:cSjcLEFvsuAb7Q3bc6O5p2LYbyjWlw5t@suleiman.db.elephantsql.com:5432/uiikgqgj
REDIS_HOST=localhost
```
4. Run the following script:
```
deno run --allow-env --allow-net --allow-read --unstable new-server.tsx -c tsconfig.json
```
