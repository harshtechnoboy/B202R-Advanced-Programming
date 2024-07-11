# Running the version control system:

## Step 1: Install libraries and dependencies

`sudo apt-get update`

### LibSSL, Zlib, Libcurl, OpenSSL

`sudo apt-get install libssl-dev zlib1g-dev libcurl4-openssl-dev`

## Step 2: Clone the project:

`git clone https://github.com/harshtechnoboy/B202R-Advanced-Programming`

## Step 3: Navigate to the path of the project:

`cd your/path/vcs`

## Step 4: Create the build directory:

`mkdir build`

## Step 5: Navigate to the path of the build:

`cd build`

## Step 6: Generate the build files:

`cmake ..`

## Step 7: Compile the build files:

`make`

## Step 8: Run the executable:

`./server 'command'`

### Some of the 'command's are:

`cat-file`

`clone`

`commit-tree`

`hash-object`

`init`

`ls-tree`

`write-tree`