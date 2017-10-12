# My Resume
https://resume.djalmaaraujo.com

## Setup
```bash
bower install
npm install -g stylus nib jeet
```

## Dev
```bash
stylus -w assets/stylesheets -c -u nib -u jeet # For stylus compilation
python -m SimpleHTTPServer # for a simple http server http://localhost:8000
```

## Deploy
I use wedeploy.com for static deployments. It's awesome. You should try. (free merchandise detected, hehe)

```bash
we deploy --project nossomosdotcc --service resume
```
