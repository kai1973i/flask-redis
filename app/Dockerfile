# Base Image
FROM python:3.8

# Working Directory inside the container
WORKDIR /app
# Copy source code to working directory
COPY . /app

# Install packages from requirements.txt
RUN pip install -r requirements.txt

# Expose port 5000
EXPOSE 5000

# start nginx
ENTRYPOINT [ "python" ]
CMD [ "app.py" ]


