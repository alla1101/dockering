#simple command running in this directory with a datafile
the objective is to understand the use of Bind

Commands:

docker build -t binder .
#you must give him full path to the shared folder
docker run --name binderj2 -d -p 4002:80 -v ~/dockering/proj_4th_apacheBind/DS_Files:/usr/local/apache2/htdocs binder

#then call localhost:4002/x.html from your browser