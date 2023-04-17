# Use golang:alpine as base image
FROM golang:alpine

# Set the working directory
WORKDIR /app

# Copy the source code to the working directory
COPY . /app

# Build the Go app
RUN go build -o main .

# Expose port 8081 for the application to listen on
EXPOSE 8080

# Run the Go app when the container starts
CMD ["go", "run", "main.go"]
