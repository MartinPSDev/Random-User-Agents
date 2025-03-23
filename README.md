# Random-User-Agents
Random User Agents for use with curl, nmap, wget etc.

## Windows

- Windows 11, Chrome:
`Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/114.0.0.0 Safari/537.36`

- Windows 11, Opera:
`Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/114.0.0.0 Safari/537.36 OPR/100.0.0.0`

- Windows 11, Brave:
`Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/114.0.0.0 Safari/537.36 Brave/100.0.0.0`

- Windows 11, DuckDuckGo (basado en Chromium):
`Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/114.0.0.0 Safari/537.36`

- Windows 10, Firefox:
`Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/114.0`

- Windows 10, Edge:
`Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/114.0.0.0 Safari/537.36 Edg/114.0.1823.58`

## macOS

- macOS Ventura, Safari:
`Mozilla/5.0 (Macintosh; Intel Mac OS X 13_4) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/16.5 Safari/605.1.15`

- macOS Monterey, Chrome:
`Mozilla/5.0 (Macintosh; Intel Mac OS X 12_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/114.0.0.0 Safari/537.36`

- macOS Big Sur, Firefox:
`Mozilla/5.0 (Macintosh; Intel Mac OS X 11.7; rv:109.0) Gecko/20100101 Firefox/114.0`

## iOS
- iOS 16, Safari:
`Mozilla/5.0 (iPhone; CPU iPhone OS 16_5 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/16.5 Mobile/15E148 Safari/604.1`

- iPadOS 16, Chrome:
`Mozilla/5.0 (iPad; CPU OS 16_5 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) CriOS/114.0.0.0 Mobile/15E148 Safari/604.1`

  Another option
  `Mozilla/5.0 (iPad; CPU OS 13_3 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/13.0.4 Mobile/15E148 Safari/604.1`
  
## Linux
- Ubuntu, Chrome:
`Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/114.0.0.0 Safari/537.36
` 
- Linux Mint, Firefox:
`Mozilla/5.0 (X11; Linux x86_64; rv:109.0) Gecko/20100101 Firefox/114.0`

## Android
- Android 13, Chrome:
`Mozilla/5.0 (Linux; Android 13; Pixel 7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/114.0.0.0 Mobile Safari/537.36`

- Android 12, Firefox:
`Mozilla/5.0 (Android 12; Mobile; rv:109.0) Gecko/114.0 Firefox/114.0`

- Android 11, Samsung Internet:
`Mozilla/5.0 (Linux; Android 11; SM-G998B) AppleWebKit/537.36 (KHTML, like Gecko) SamsungBrowser/16.0 Chrome/92.0.4515.166 Mobile Safari/537.36`

## Others
- Googlebot:
`Mozilla/5.0 (compatible; Googlebot/2.1; +http://www.google.com/bot.html)`

- Bingbot:
`Mozilla/5.0 (compatible; bingbot/2.0; +http://www.bing.com/bingbot.htm)`

## Usage
- nmap:

`nmap -p 80,443 --script http-headers --script-args http.useragent="Mozilla/5.0 (Windows NT 10.0; Win64; x64)" target.com
`   
- curl:
  
`curl -A "Mozilla/5.0 (Linux; Android 14; SM-G991B) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.0.0 Mobile Safari/537.36" http://target.com
`

- wget:

`wget --user-agent="Mozilla/5.0 (iPhone; CPU iPhone OS 17_2 like Mac OS X) AppleWebKit/537.36 (KHTML, like Gecko) Version/17.2 Mobile/15E148 Safari/537.36" target.com
`






