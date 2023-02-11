# simple_weather_app
学习 [The Coding Train: Working with Data and APIs in JavaScript](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6YxDKpFzf_2D84p0cyk4T7X) 最终所做的练习
原项目使用了DarkSky API，但该API目前已经不能使用，所以使用了[OpenWeather API](https://openweathermap.org/api)

## 使用
下载该项目
```
git clone https://github.com/Ziur02/simple_weather_app.git
```

使用npm安装所需的包
```
npm install
```
新建.env文件，按照.env_sample中的格式将YOUR_API_KEY_HERE部分替换为自己的key，该key可以在登陆OpenWeather网站后在[这里](https://home.openweathermap.org/api_keys)获取

启动项目
```
node index.js
```
