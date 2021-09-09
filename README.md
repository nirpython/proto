XPLUR Project

Directions to use:
The project has been attached as a RAR file
Please unzip it in you local system 

- GO TO proto directory
cd proto

if you are in linux 
$ source venv/Scripts/activate
or windows 
venv\Scripts\activate.bat


Load the requirements.txt file for dependancies 

pip install -r requirements.txt  // it will load all required dependenies for running the app

then 

To run app in your local machine

$python app.py 

It will activate development server on port on http://127.0.0.1:1224/

Api End points:


#Retrieve all the products   http://127.0.0.1:1224/products

#Retrieve one product  http://127.0.0.1:1224/product/Name

#Rreate a product  http://127.0.0.1:1224/product

#Update a product  http://127.0.0.1:1224/update/name

#Delete a product  http://127.0.0.1:1224/delete/name


--------------------------------------------------------------------------------------------
You can alternatively run this app in docker  

Below are the steps to follow: 

(venv) G:\proto>docker ps
CONTAINER ID   IMAGE       COMMAND           CREATED         STATUS         PORTS
              NAMES
bd27d3d7e0ea   proto_app   "python app.py"   4 minutes ago   Up 8 seconds   0.0.0.0:5000->5000/tcp, :::500
0->5000/tcp   proto_app_1

(venv) G:\proto>
