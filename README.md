# How to configure FoxyProxy Chrome extension on Chrome browser?

[FoxyProxy](https://yilu.us/integration/configure-foxyproxy-extension-yilu-proxy) is a proxy extension that makes managing and switching multiple proxies settings quick and easy. This article will show you how to set up FoxyProxy chrome extension with YiLu Socks5 proxy on Google Chrome browser. 
![FoxyProxy](https://api.yilu.us/wp-content/uploads/2022/10/Foxyproxy-yilu-proxy-1200x675.jpg)

Download and install Yilu Proxy client from its official site: https://yilu.us/download

## YiLu Proxy Settings:

### Set YiLu Proxy “settings”
Contains Proxy port , port forward, bind address(127.0.0.1), Proxy Engine Settings and ProxyRules.
![FoxyProxy](https://api.yilu.us/wp-content/uploads/2022/10/%E5%9B%BE%E7%89%87.png)

### Local port forward

Right-click an IP and select “Connect” or directly double-click an IP.
![FoxyProxy](https://api.yilu.us/wp-content/uploads/2022/10/%E5%9B%BE%E7%89%87-1.png)

### Multi-port forward

Right-click an IP and select a proxy port.  
![FoxyProxy](https://api.yilu.us/wp-content/uploads/2022/10/%E5%9B%BE%E7%89%87-2.png)

### Rotating IP port forward

Select a country, state, city, and the number of refreshing IPs, Then click “Refresh (HTTP/SOCKS5)”.  
**Note:**
Rotating residential IP supports selecting state and city, but rotating datacenter IP only supports selecting country.  
Rotating IPs support Socks5 and HTTP protocols.  
![FoxyProxy](https://api.yilu.us/wp-content/uploads/2022/10/%E5%9B%BE%E7%89%87-3.png)

Then forward an IP to a proxy port:  
![FoxyProxy](https://api.yilu.us/wp-content/uploads/2022/10/%E5%9B%BE%E7%89%87-4.png)

### Port Forward List
You can check proxy port’s information in “Port Forward List” on the top right.

## FoxyProxy Settings
Firstly, install FoxyProxy extension in Chrome browser: https://chrome.google.com/webstore/detail/foxyproxy-standard/gcknhkkoolaabfmlnjonogaaifnjlfnp

### Open FoxyProxy's Options.
![FoxyProxy](https://api.yilu.us/wp-content/uploads/2022/10/%E5%9B%BE%E7%89%87-5.png)

### Click “Add New Proxy”.
![FoxyProxy](https://api.yilu.us/wp-content/uploads/2022/10/%E5%9B%BE%E7%89%87-6.png)

### Fill in proxy details.

Select “Manual Proxy Configuration”  
Host or IP Address: 127.0.0.1  
Port:1080  
The port is set in YiLu Proxy, you can also enter another proxy port, such as 5500, 5501, or 5502.  
Select “SOCKS proxy?” and “SOCKS v5”  
Then click “Save”.  
![FoxyProxy](https://api.yilu.us/wp-content/uploads/2022/10/%E5%9B%BE%E7%89%87-7.png)  

Then you can see the configured proxy in FoxyProxy proxies.  
![FoxyProxy](https://api.yilu.us/wp-content/uploads/2022/10/%E5%9B%BE%E7%89%87-8.png)

Then I add more proxies in FoxyProxy using different ports.  
![FoxyProxy](https://api.yilu.us/wp-content/uploads/2022/10/%E5%9B%BE%E7%89%87-9.png)

### Click the FoxyProxy extension icon and choose a configured proxy.  
![FoxyProxy](https://api.yilu.us/wp-content/uploads/2022/10/%E5%9B%BE%E7%89%87-10.png)

### Check proxy IP

Then you can check the IP on Chrome browser by entering “ipinfo.io”, and that is the IP forward to port 1080 in YiLu Proxy.  
![FoxyProxy](https://api.yilu.us/wp-content/uploads/2022/10/%E5%9B%BE%E7%89%87-11.png)

The article is from https://yilu.us/integration/configure-foxyproxy-extension-yilu-proxy  

YiLu [Socks5 proxy trial](https://yilu.us/trial): https://yilu.us/trial  


