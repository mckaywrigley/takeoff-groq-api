# Takeoff: Groq API

This module is a guide to the Groq API.

## Resources

- [Takeoff](https://JoinTakeoff.com)
- [Groq Docs](https://console.groq.com/docs/quickstart)
- [Groq API Reference](https://console.groq.com/docs/libraries)
- [Groq API Cookbook](https://github.com/groq/groq-api-cookbook)

## ## Recommendations

We recommend using [Cursor](https://cursor.sh/) to write code.

## Prerequisites

You will need a Groq API Key.

Get one [here](https://console.groq.com/keys).

Copy the `.env.example` file to `.env`.

```bash
cp .env.example .env
```

In `.env`, fill in the API key.

```bash
GROQ_API_KEY=your-groq-api-key
```

## Install Packages

```bash
npm i
```

## Structure

The example code is in the `examples` folder.

Your code is in the `me` folder.

## Run Code

Install `tsx` to run the examples.

```bash
npm i -g tsx
```

Example: Run the `audio-create-speech-example` and `audio-create-speech-me` files.

Copy the relative path of the file.

For the example code, run the following command:

```bash
tsx examples/audio/create-speech.ts
```

For your code, run the following command:

```bash
tsx me/audio/create-speech.ts
```
