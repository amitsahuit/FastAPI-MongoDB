# FastAPI-MongoDB

## intial setup of repo in local
```
$ git clone https://github.com/amitsahuit/FastAPI-MongoDB.git
```

### make sure u have installed MongoDB in localhost and able to connect form compass. In my case MongoDB url is :
```
#localhost
mongodb://localhost:27017/

#cloud
mongodb+srv://amit:<<password>>@todolist.lwjuyzf.mongodb.net
```

## installing dependencies and starting FastAPIapp
```
cd  FastAPI-MongoDB
py -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```

## Test URL
```
http://127.0.0.1:8000/docs

```