# flutter_web


1. STEP1: flutter clean then flutter pub get

2.
```
? What do you want to use as your public directory? build/web
? Configure as a single-page app (rewrite all URLs to /index.html)? yes
? Set up automatic builds and deploy with GitHub? no
? File build/web/index.html already exists. Overwirte? no
```
3. firebase.json ဖိုင်က 

```
{
  "hosting": {
    "site": "hmwtdz",
    "public": "build/web",
```
4. firebase deploy --only hosting:thisisname



