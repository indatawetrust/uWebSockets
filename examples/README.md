##### build echo.cpp
```
g++ -L/usr/local/opt/openssl/lib -I/usr/local/opt/openssl/include \
-std=c++11 echo.cpp -o echo  -lpthread -L. -luWS -lssl -lcrypto -lz -luv
```

##### build multithreaded_echo.cpp
```
g++ -L/usr/local/opt/openssl/lib -I/usr/local/opt/openssl/include \
-std=c++11 multithreaded_echo.cpp -o multithreaded_echo  -lpthread -L. -luWS -lssl -lcrypto -lz -luv
```
