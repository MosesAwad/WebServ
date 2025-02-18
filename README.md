>WebServ is a high-performance, non-blocking web server built in C++ with robust support for GET, POST, PUT, and DELETE methods. Designed for both Linux and macOS, 
>it leverages kqueue and epoll for efficient I/O multiplexing, ensuring seamless handling of high-concurrency workloads. A key feature of WebServ is its Nginx-like 
>configuration system, allowing users to customize server behavior through directives.

>The server also includes comprehensive CGI handling, where configured scripts are executed through a dedicated handler using process forking and piped output management. 
>To ensure reliable data transmission, WebServ implements request and response body collation, preventing message fragmentation in concurrent environments. Additionally, 
>it supports chunked transfer encoding for handling large payloads efficiently.

>WebServ has been rigorously tested using custom tools, Nikto, and Linux Siege, demonstrating its stability under high loads. With no segmentation faults and consistent 
>performance under stress, it is a reliable and scalable solution for web serving.
