# Memory Uploader - Installation

**Version:** 3.6.2  
**Author:** @_ar1sk\_ on Discord  

Memory allows you to find trending models on the Roblox store and reupload them with a "tweak" ;)

---

## Installation

1. **Install [Node.js](https://nodejs.org/en/) 22.19.0**  
   - [Windows Installer](https://nodejs.org/dist/v22.19.0/node-v22.19.0-x64.msi)  
   - [Windows Zip](https://nodejs.org/dist/v22.19.0/node-v22.19.0-win-x64.zip)  
   - [v22 Archive](https://nodejs.org/en/download/archive/v22.19.0/)

2. **Create a folder** anywhere on your PC (desktop recommended) and name it `Memory Uploader`.

3. **Download the files**  
   - Get `package.json` and `index.js` from @_ar1sk_ on Discord.

4. **Install dependencies**  
   Open a terminal in the folder and run:  
   ```bash
   npm install
   ```
   or, if using pnpm:  
   ```bash
   pnpm install
   ```

5. **Start the tool**  
   ```bash
   npm start
   ```
   or
   ```bash
   node index.js
   ```

---

## Usage

- Follow the interactive prompts to select accounts and upload models.  
- Progress bars will display current upload/scan stats.  
- Session summary is provided at the end of each run.

---

## Dependencies

- [noblox.js](https://www.npmjs.com/package/noblox.js) – Roblox API library  
- [node-fetch](https://www.npmjs.com/package/node-fetch) – Fetch API for Node.js  
- [axios](https://www.npmjs.com/package/axios) – HTTP client  
- [rbxm-parser](https://www.npmjs.com/package/rbxm-parser) – Roblox model parsing  
- [dotenv](https://www.npmjs.com/package/dotenv) – Environment variable loader  
- [@google/generative-ai](https://www.npmjs.com/package/@google/generative-ai) – AI model integration  

---

## Support

- Discord: @_ar1sk_  
