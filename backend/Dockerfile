# syntax=docker/dockerfile:1

FROM registry-vpc.cn-huhehaote.aliyuncs.com/wangshize/py-file-cache:v1

#RUN sed -i 's#http://deb.debian.org#http://mirrors.aliyun.com/#g' /etc/apt/sources.list && apt-get clean

#RUN apt-get update && apt-get install -y libpq-dev gcc vim apache2-utils && rm -rf /var/lib/apt/lists/*
#
#WORKDIR /app
#
#COPY requirements.txt requirements.txt
#RUN pip3 install -r requirements.txt

COPY . .

CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]