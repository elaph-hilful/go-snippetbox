# Snippetbox Web Application

This is a simple web application built using [Go](https://go.dev/). It demonstrates the basic components required to set up a web server, including a handler, a router, and the server itself.

## Components

1. **Handler**: Responsible for executing application logic and writing HTTP response headers and bodies. In this application, the `home` function serves as the handler.

2. **Router (ServeMux)**: Maps URL patterns to corresponding handlers. The `http.NewServeMux()` function is used to create a new router, and routes are registered using `mux.HandleFunc()`.

3. **Web Server**: The application includes a built-in web server that listens for incoming requests. This eliminates the need for an external server like [Nginx](https://nginx.org/) or [Apache](https://httpd.apache.org/).

## Usage

To run the application, execute the following command in your terminal:

```bash
go run main.go
