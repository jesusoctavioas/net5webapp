Steps:
dotnet new webapp --framework net5.0

docker build -t net5webapp .
docker run -d -p 80:5000 net5webapp
