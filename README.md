## GOBrute v1

A brazingly fast Wordpress login bruteforce tool written in Go. 

### Info: 
1. Find usernames **https://target.com/wp-json/wp/v2/users**.
2. Generate passwords related to username using [this tool](https://github.com/anonymouseshrivastav/password-generator).
3. Now you can use this tool.
4. Give a star if its useful.

### Supported in:
Linux <br/>
Termux <br/>
Mac Os <br/>
Windows <br/>


### Installation:

```bash
pkg install golang git
```

```bash
git clone https://github.com/anonymouseshrivastav/GOBrute
```

```bash
cd GOBrute
```

```bash
go build
```

### Usage:
```bash
GOBrute --url <login page url> -u <username> -p <password list> -t <threads>
```
```bash
GOBrute --url https://target.com/wp-login.php -u admin -p passwords.txt -t 40
```


### Access the tool from any directory:

```bash
cp WPBrute /data/data/com.termux/files/usr/bin/WPBrute
```

### More Info:
1. Adding more features.
2. Auther: Anon Shrivastav.
3. Telegram: https://t.me/anonshrivastavofficial.
