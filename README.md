[grokdebugger.com](https://www.grokdebugger.com)

This client-side application uses WebAssembly to run PCRE RegEx in the browser. It can help you debug your Grok patterns.

**Features:**

- Real-time processing (see changes as you type)
- Autocomplete
- Match highlighting
- Syntax highlighting
- Multiline debugging
- 20+ pattern sets (AWS, Grok, firewalls, Java, etc.)
- Add more pattern sets with a URL
- Save and use your own custom patterns


![screenshot](screenshot.png)



**NOTE to DD implementation:**

- run xcode-select --install if the npm install doesnt work
- Currently using v18.4.0


Current implemented DD-GROK-PARSER 
- [ ] date("pattern"[, "timezoneId"[, "localeId"]])
- [ ] regex("pattern")
- [x] notSpace
- [ ] boolean("truePattern", "falsePattern")
- [ ] numberStr
- [x] number
- [ ] numberExtStr
- [ ] numberExt
- [ ] integerStr
- [x] integer
- [ ] integerExtStr
- [ ] integerExt
- [x] word
- [x] doubleQuotedString
- [x] singleQuotedString
- [x] quotedString
- [x] uuid
- [x] mac
- [x] ipv4
- [x] ipv6
- [x] ip
- [x] hostname
- [x] ipOrHost
- [x] port
- [x] data
