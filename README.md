# URLtoPDF

URLtoPDF is a Discord bot which currently turns your given link into PDF and retunrs back. 
## Features supported:
- [x] Creating PDF from URls
- [ ] [WIP] Bypassing Link Shorteners 
  - [x] Bit.ly & Linkvertise works but needs other services
- [ ] [WIP] User verification from Google Sheets Data (Inspired from Advising Server BOT)  
- [ ] Custom PDF Size & User Agent
### Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the requiremnts.

```bash
pip install -r requirements.txt
```
### Setting up config:
- Create a New Discord Application from [Discord Developer Dashboard](https://discord.com/developers/applications) and add a bot to it.
- Copy the BOT TOKEN and replace it in BOT_TOKEN 
```python 
BOT_TOKEN = "Njk3ODIxNjk2NzQ0NDg5MDIx.Xo83GQ.rDrAFjgLo082lHb7yr-IV4arAcg"
```
## Usage
- Make a PDF 
  - ```python >mpdf [url] ```


![USAGE](https://github.com/TanjimReza/URLtoPDF/blob/main/github.png)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[GNU GPLv3](https://github.com/TanjimReza/URLtoPDF/blob/main/LICENSE)
