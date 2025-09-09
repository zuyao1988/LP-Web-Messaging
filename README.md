# LP-Web-Messaging


# Web Messaging Login Page - Setup Instructions

Choose one of the following options to deploy your web messaging login page:

## Option 1: Local Static Server (http-server)

1. Install http-server globally:
```bash
npm install -g http-server
```

2. Start the server:
```bash
http-server -p 8002 -P http://localhost:8002/web-messaging-login-page.html
```

3. Access your page at:
```text
http://localhost:8002/web-messaging-login-page.html
```

## Option 2: Nginx Server
1. Configure Nginx by editing your sites-available configuration:
```text
nginx\sites-available\live-person.com
```

2. Enable the site and restart Nginx:
```bash
sudo ln -s /etc/nginx/sites-available/live-person.com /etc/nginx/sites-enabled/
sudo systemctl restart nginx
```

## Option 3: GitHub Pages
1. Enable GitHub Pages in your repository:
* Go to your repo → Settings → Pages
* Under "Source", select the branch: main
* Click Save

2. Wait a few minutes for GitHub Pages to deploy (GitHub Pages may take 1-2 minutes to deploy after configuration)

3. Site will be available at:
```text
https://zuyao1988.github.io/LP-Web-Messaging/web-messaging-login-page.html
```

Alternative Local Path:
```text
/code/web-messaging-login-page.html
```

