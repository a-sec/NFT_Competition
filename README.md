# Competition App

A simple Flask app with [Application Security](https://docs.app-security.trendmicro.com/) embedded. 

## Start app

Start the app using the following command:

```
docker run \
--name Competition \
-d -p 5000:5000 \
-e TREND_AP_KEY=<AP_KEY> \
-e TREND_AP_SECRET=<AP_SECRET> \
a-sec/nftcomp
```


