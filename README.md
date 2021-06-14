# Silent is a simple TCP reverse shell written in C.
![Alt Text](https://media.giphy.com/media/Kmr5zGPaFDWYiVBVIB/giphy.gif)
### In both files IP need to be changed to yours.

### For example:

### server.c

###### server_address.sin_addr.s_addr = inet_addr("192.168.0.100");

### client.c

###### ServIP = "192.168.0.100";

## Installation
```bash
git clone http://github.com/R4v3nG/silent.git
sudo apt-get install gcc-mingw-w64-i686
cd silent/server
gcc -o server server.c
cd ../client
i686-w64-mingw32-gcc -o client.exe client.c -lwsock32 -lwininet
```

## Usage
# Linux
```bash
./server
```
# Windows
```bash
client.exe
```
# Silent uses 50005 port
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)

<a href="https://www.buymeacoffee.com/R4v3nG" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
