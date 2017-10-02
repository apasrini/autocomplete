# autocomplete
choose from a large but fixed set

Step 1 : git clone the "autocomplete" repo 

Step 2 : do "npm install"

Step 3 : Now autocomplete repo in your local would get a node_modules folder. Add loopback_connector_suggest_cities folder (Zip provided) into the node_modules folder.

Step 4 : Do "npm install trie-search"

Step 5 : Come to autocomplete folder and do a "node ."

Step 6 : open the explorer http://localhost:3000/explorer/#!/suggest95cities/suggest_cities_find

Step 7 : Under suggest_cities do a GET on /suggest_cities

Step 8 : You could try out with filter "{"where":{"start":"v"},"limit":3}"
