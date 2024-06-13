
# Webhook_test using NGROK
This is Readme file for webhook test with jenkins and github.

# Download ngrok
```
wget https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-amd64.tgz
```
# Extract ngrok
```
tar -xvzf ngrok-v3-stable-linux-amd64.tgz
```
# Move ngrok to a directory in your PATH
```
sudo mv ngrok /usr/local/bin/
```
# Verify installation
ngrok --version

# (Optional) Connect your ngrok account. You will get auth token here: 
https://dashboard.ngrok.com/get-started/your-authtoken
```
ngrok authtoken 2h57erXJyiB2azR7vw25VoYrfaa_6EFhz54AuuUVJS1KEXawB
````
# Start ngrok
```
ngrok http 8080
```
then configure payload url in github webhook section
(https://9e09-103-139-242-126.ngrok-free.app/github-webhook/)

# Find the Process ID (PID):
```
ps aux | grep ngrok
```
# Kill the Process:
```
kill -9 PID
```
Replace PID with the actual process ID of the ngrok process.

