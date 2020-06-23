FROM mcr.microsoft.com/dotnet/core/sdk
WORKDIR /src 
COPY . .
RUN dotnet publish -c Release -o out

WORKDIR /src
COPY /src/out .

ENTRYPOINT ["dotnet", "hello-world.dll"]


# FROM golang:latest
# WORKDIR /go/src/hello
# COPY . .
# RUN go get -d -v ./...
# RUN go install -v ./...
# CMD ["hello"]
