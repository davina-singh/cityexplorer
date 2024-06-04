Need to get deployment working:
Update client code to point to URL from Render app. 
Either use an environment variable that you set on Render and locally, then read in your code, or check in the code for the NODE_ENV value, and if it's production, use the Render.com URL. 
If it's not, use localhost.
