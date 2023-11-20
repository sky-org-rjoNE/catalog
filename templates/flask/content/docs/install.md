## Testing application on local machine

### Prerequisites:
- Docker

### Build Docker image
docker build -t flask:0.0.1 .

### Run Docker image
docker run -d -p 5000:5000 flask:0.0.1