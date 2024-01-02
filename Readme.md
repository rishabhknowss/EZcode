
# EZcode

EZcode is a command-line tool for generating and debugging code using Google Generative AI

## Installation

```
npm install ezcode
```

## Setup

To use EZcode, you need to set up your environment by creating a `.env` file with your [Gemini Pro](https://ai.google.dev/) API key:

```dotenv
API_KEY="YOUR_GEMINI_PRO_KEY"
```

## Usage

```
npx ezcode -f "<filename>" -p "<prompt>"
```
Add filename to `edit/write` and prompt `what to edit/write`
```
npx ezcode -f "index.js" -p "create a simple express server"
```
