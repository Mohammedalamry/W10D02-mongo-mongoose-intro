# Install Mongo

## Install with Homebrew

- [Homebrew: The missing package manager for macOS](https://brew.sh/)
- [Mongo Manual Install](https://docs.mongodb.com/manual/installation/)


* Check if homebrew is installed: `brew`

	* If not, install [Homebrew](https://brew.sh/) by following the instructions on the web page
	* If brew is already installed `brew upgrade`.
	* Run on the terminal before `brew tap mongodb/brew`

* **Install Mongodb on Mac OS X:** `brew install mongodb-community@4.2`

## Set data location

In terminal type `brew services start mongodb-community@4.2` to run the mongo server.

<!-- You will probably get an error saying
> "Data directory `/data/db` not found., terminating"
	- if so, you will need to make the directories in your **root** directory as follows (do these commands anywhere):

* Create data directories (at the root level)
	* `sudo mkdir /data`
	* `sudo mkdir /data/db`

* Next, set root permissions
	* `sudo chmod -R 777 /data` -->

Run the mongo server again: `mongod`.

Should see: "waiting for connections on port 27017"

## Open and close mongo

* Open another terminal tab `cmd + T` and type `mongo`

* To quit `mongo`, type `exit` or `quit()`.  

* To quit `mongo` hit `control+c`

Finished!


