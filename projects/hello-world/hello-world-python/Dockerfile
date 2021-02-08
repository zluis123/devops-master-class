#Base image para python
FROM python:alpine3.10
#Define o workdir do docker
WORKDIR /app 
#Copias os requirements para a workdir
COPY requirements.txt /app/requirements.txt
#instala os requirements presentes no txt file
RUN pip install -r requirements.txt
#copia todo o conteudo do pasta para o workdir
COPY . /app
#abre a porta 5000
EXPOSE 5000
#lanca a aplicacao
CMD python ./launch.py

#COPY requirements.txt /app/requirements.txt
#ENTRYPOINT ["python", "./launch.py"]
