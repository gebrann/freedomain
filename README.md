# freedomain
Get your own '.fioo.org' subdomain


A quick way to register and get a subdomain: For example, if you want to use the subdomain `example.fioo.org`, create a new file at domains/fioo.org/example.fioo.org.json and fill it with the code below.


```
{
    "description": "enter your description",
    "domain": "fioo.org",
    "subdomain": "Your-Subdomain",
    "owner": {
        "username": "ghost",
        "repo": "https://github.com/username/repo (optional)",
        "email": "you@example.com"
    },
    "record": {
        "TXT": [
            "enter-your-record"
        ]
    },
    "proxied": true
}
```


Change the description and subdomain (for example, if you want to use `example.fioo.org`, then in the subdomain column enter `example`), In the username section, fill in your username. It would be better if you use the username you used to create the pull request and in the `repo` and `email` sections please fill in your repository (if you are using github pages) but if you don't want to fill in the repo, then delete the repo section, and enter your active email, you can use a personal email, business email, or anything with any provider such as gmail or yahoo, example code if you don't want to use `repo` below


```
{
    "description": "enter your description",
    "domain": "fioo.org",
    "subdomain": "Your-Subdomain",
    "owner": {
        "username": "ghost",
        "email": "you@example.com"
    },
    "record": {
        "TXT": [
            "enter-your-record"
        ]
    },
    "proxied": true
}
```


For records, you can adjust your needs accordingly. If you need `TXT`, use `TXT`. If you use `CNAME`, use the `CNAME` record, and so on. In the proxied section, you can also set it to `true` or `false` according to your needs. If you use `true`, you will get the benefits of Cloudflare's proxied.

This repository is under development, please be patient!😊, but if you want to make a pull request to register your domain, it can still be accepted. 
