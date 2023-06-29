# HTTP-Proxy-Server-With-Caching-Support
This is the repository for the documentation and Code of the Project "HARDWARE ACCELERATED HTTP/1.1 PROXY SERVER" 


Features:

Acts as an intermediary between client applications and remote servers.
Caches responses to improve performance.
Handles HTTP requests and responses.
Supports HTTP methods such as GET and POST.
Manages caching and revalidation of resources.
Multithreaded design to handle multiple client connections simultaneously.

Installation:

Clone the repository:

    git clone https://github.com/roguehunter7/HTTP-Proxy-Server-With-Caching-Support.git

Navigate to the project directory:

    cd HTTP-Proxy-Server-With-Caching-Support/src


Compile the source code and Start the proxy server:

    chmod +x ./run.sh
    ./run.sh

Alternate option:
Assuming you have docker installed you can also just run the following:

      cd HTTP-Proxy-Server-With-Caching-Support/
      sudo docker-compose up


Usage:

Configure your web browser to use the proxy server:
        Open your browser's settings/preferences.
        Locate the network/proxy settings.
        Set the proxy server address to localhost or 127.0.0.1 and the port to 12345.

Open your web browser and start browsing. The proxy server will intercept and handle the HTTP requests.

Configuration

The proxy server listens on port 12345 by default. If you need to change the port or modify other settings, you can edit the proxy.h file and recompile the code.

Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

License

This project is licensed under the GPLv3 License.
