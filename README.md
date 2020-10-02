# RTSP_Streaming_Module

Objective : Building a RTSP streaming module which can take the following link and iterate it on the front end into the multiple of n.
Link : rtsp://freja.hiof.no:1935/rtplive/_definst_/hessdalen03.stream

# Installation
1. Download Source Code (zip) https://github.com/Anushakt/RTSP_Streaming_Module.git
2. Open a command prompt and enter the following: :  
   npm install -g http-server
3. Change to the directory containing the project
4. Start the server with this command:
   http-server
5. Open your browser and go to the address http://localhost:8080   

# Dockerizing
1. Open the windows poweshell and got the project directory
2. Enter below commands
    npm run
    docker build . -t rtspstreaming (rtspstreaming is an image name)
    docker run rtspstreaming
    docker run rtspstreaming -p 8080:80
3. Open your browser and go to the address http://localhost:8080
