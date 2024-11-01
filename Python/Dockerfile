FROM python:3.9

# Corrected default_typ to default_type.
WORKDIR /app

# typo error "appy.py" to "app.py"
COPY app.py /app 

#typo error "netiface" to "netifaces"
RUN pip install flask netifaces

# EXPOSE "eight thousand"
EXPOSE 8000

# CMD ["pythn", "app.py"]
CMD ["python", "app.py"]