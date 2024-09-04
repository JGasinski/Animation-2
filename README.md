To run this animation

with Python
- open terminal
- navigate into the folder with your .html files
  (using terminal/cmd) and execute the following command: python -m SimpleHTTPServer 1337
  if you're using Python 3.x or higher, you'd use python -m http.server 1337
- now you should be able to access your own files via http://localhost:1337/myfile.html in Chrome, Firefox or any other web browser.

with Node.js and npm

- Open a terminal window and enter the following command to install serve globally:
  npm install -g serve
- Navigate to the directory containing your HTML file.
  cd /path/to/your/directory
- Now, it’s time to serve your project. In the terminal, enter the following command:
  serve
- After running the serve command, you should see an output similar to this:

   
                                              
     Serving!                                 
                                              
     - Local:            http://localhost:5000
     - On Your Network:  http://192.168.0.5:5000
                                              
     Copied local address to clipboard!       
   

- Open your web browser and navigate to http://localhost:5000. You should see your HTML file served as a website!
- Once you’re done, you can stop the server by going back to the terminal and pressing CTRL + C.
