#Base image to start (last python 3)
FROM python:3

#Create a folder to put the app
RUN mkdir /opt/hello_ap

#Select a workdir to run all the commands
WORKDIR /opt/hello_app

#Add from my local computer to WORKDIR
ADD requirements.txt .

RUN pip install -r requirements.txt

#Add local files to the container
ADD . .

#Expose app from port 5000
EXPOSE 5000

#Run the app
CMD ["python", "hello.py"]

