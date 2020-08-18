         ___        ______     ____ _                 _  ___  
        / \ \      / / ___|   / ___| | ___  _   _  __| |/ _ \ 
       / _ \ \ /\ / /\___ \  | |   | |/ _ \| | | |/ _` | (_) |
      / ___ \ V  V /  ___) | | |___| | (_) | |_| | (_| |\__, |
     /_/   \_\_/\_/  |____/   \____|_|\___/ \__,_|\__,_|  /_/ 
 ----------------------------------------------------------------- 


Hi there! Welcome to AWS Cloud9!

To get started, create some files, play with the terminal,
or visit https://docs.aws.amazon.com/console/cloud9/ for our documentation.

Happy coding!

TUTORIAL
https://developer.okta.com/blog/2018/12/20/crud-app-with-python-flask-react

RUN MONGODB
docker-compose up

REQUIRED BY MongoRepository, as it reads an environment variable
export MONGO_URL=mongodb://mongo_user:mongo_secret@0.0.0.0:27017/ 

RUN FLASK - REST API
FLASK_APP=$PWD/app/http/api/endpoints.py FLASK_ENV=development  python3 -m flask run --port 4433

