# Webhook_test
This is Readme file for webhook test with jenkins and github

# Download ngrok
wget https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-amd64.tgz

# Extract ngrok
tar -xvzf ngrok-v3-stable-linux-amd64.tgz

# Move ngrok to a directory in your PATH
sudo mv ngrok /usr/local/bin/

# Verify installation
ngrok --version

# (Optional) Connect your ngrok account
ngrok authtoken <your_auth_token>

# Start ngrok
ngrok http 8080

then configure payload url in github webhook section
(https://9e09-103-139-242-126.ngrok-free.app/github-webhook/)

