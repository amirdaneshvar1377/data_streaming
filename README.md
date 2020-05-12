# data_streaming

# dependencies: 
1. node -v: v10.16.3
2. npm -v: 6.9.0
3. OBS Studio (streaming desktop app)

# steps for run the stream app

1. clone the whole of project into streaming dir
2. create shell session cd api dir and then: npm install && npm start
3. create new shell session, cd client and then: npm install && npm start
4. create another shell session, cd rtmpserver and then: npm install && npm start

after this steps browse in http://localhost:3001
login with google account create new stream and keep in mind stream id and then go to OBS Studio write custom url :: 


url : rtmp:localhost

key : (your stream id)
