# Copy the entire folder as zip into docker engine machine
Pre-req's for engine machine are wget and unzip packages 

- Books-App
docker build -t kalyansulluru/sampleapp:11.0 .

docker run -itd --name=testapp -p 80:80 kalyansulluru/sampleapp:11.0

http://192.168.0.12:80

- Team-App
docker build -t kalyansulluru/teamapp:11.0 .

- Closing-App
docker build -t kalyansulluru/closingapp:11.0 .


============================= DOCKER PUSH
