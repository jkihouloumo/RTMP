# Prerequisites

Install [__OBS__](https://obsproject.com) version 24.0.3. 

# OBS Configuration 

In Settings->Stream, change to :

Service: Custom

Server: rtmp://localhost/live

Key stream: STREAM_NAME

# Publish the RTMP stream

Start the NODE server:
```
node app.js
```

Then, select a source on OBS and start the streaming.

The flow is available at:
```
http://127.0.0.1:8000/admin
```
