# O-MI subscription demo

A single web page dashboard-like demo with O-MI subscription. Subscribes to all value changes on a O-MI node and creates an automatically updating gauge for each different InfoItem.

# How to run


1. Just serve the html file with your preferred method:
   
   For example, **choose one** of these:

   * Python3 
      ```
      python -m http.server 8000
      ```

   * Python2 
      ```
      python -m SimpleHTTPServer 8000
      ```

   * Node 
      ```
      npm install http-server -g
      http-server -p 8000
      ```

2. Go to http://localhost:8000/

3. If your O-MI Node has different url than http://localhost:8080/ : Open developer console and call `connectWebsocket("ws://url")`

4. Make some write requests to the O-MI node (on http://localhost:8080/)

