FROM mcr.microsoft.com/dotnet/core/sdk
WORKDIR /src 
COPY . .
RUN dotnet build 
ENTRYPOINT ["dotnet", "run"]


# FROM golang:latest
# WORKDIR /go/src/hello
# COPY . .
# RUN go get -d -v ./...
# RUN go install -v ./...
# CMD ["hello"]
