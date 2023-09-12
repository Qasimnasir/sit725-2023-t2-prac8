Git clone te repository (https://github.com/Qasimnasir/sit725-2023-t2-prac8.git)
Change directory to Practical.
First Create a Dockerfile include (Source file, npm, and path)
Then use Docker build command where you specify your container name like i did "Video-streaming" and include your dockerfile path which you used as Dockerfile and use dote at the end in this command then execute.
(docker build -t video-streaming --file Dockerfile .)
Then Use the docker run command where you include host port and runnig port and also include your container name and then run.(docker run -d -p 3000:3000 video-streaming)
Check your local host to see the application.
