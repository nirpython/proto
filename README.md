# Hello sir 
i upload a zip file of the project 
please unzip it in you local system 

- GO TO proto directory
cd proto

if you are in linux 
$ source venv/Scripts/activate
or windows 
venv\Scripts\activate.bat



Now load the requirements.txt file for dependancies 

pip install -r requirements.txt  // it will load all dependenies for running app

then 
if you want to run app in you local mechine

$python app.py 

it will activte devlopment server on port on http://127.0.0.1:1224/

Api End points:


#retrieve all the products   http://127.0.0.1:1224/products


#retrieve one product  http://127.0.0.1:1224/product/Name

#create a product  http://127.0.0.1:1224/product


#update a product  http://127.0.0.1:1224/update/name

#Delete a product  http://127.0.0.1:1224/delete/name




--------------------------------------------------------------------------------------------
Sir also you can run this app in docker  
here is the detail: 

(venv) G:\proto>docker ps
CONTAINER ID   IMAGE       COMMAND           CREATED         STATUS         PORTS
              NAMES
bd27d3d7e0ea   proto_app   "python app.py"   4 minutes ago   Up 8 seconds   0.0.0.0:5000->5000/tcp, :::500
0->5000/tcp   proto_app_1

(venv) G:\proto>
