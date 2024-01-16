# Prerecorded Flask Starter

This sample demonstrates interacting with the Deepgram API from Flask to make transcriptions of prerecorded files. It uses the Deepgram Python SDK, with a javascript client built from web components (no `npm` requirements).

## Sign-up to Deepgram

Before you start, it's essential to generate a Deepgram API key to use in this project. [Sign-up now for Deepgram and create an API key](https://console.deepgram.com/signup?jump=keys).

## Quickstart

### Manual

Follow these steps to get started with this starter application.

#### Clone the repository

Go to GitHub and [clone the repository](https://github.com/deepgram-starters/prerecorded-flask-starter).

#### Install dependencies

Install the project dependencies.

```bash
pip install -r requirements.txt
```

#### Edit the config file

Copy the code from `sample.env` and create a new file called `.env`. Paste in the code and enter your API key you generated in the [Deepgram console](https://console.deepgram.com/).

```bash
DEEPGRAM_API_KEY=%api_key%
```

#### Run the application

Once running, you can [access the application in your browser](http://localhost:8080/).

```bash
flask run -p 8080
```

## Setting up a Python developer environment

Install `virtualenv`.

```bash
pip install virtualenv
```

Create a virtual environment.

```bash
python -m venv env
```

Activate the environment.

```bash
source env/bin/activate
```

Then install your dependencies with pip and they will be installed in the virtual environment rather than your user.

```bash
pip install -r requirements.txt
```

## What is Deepgram?

Deepgram is an AI speech platform which specializes in (NLU) Natural Language Understanding features and Transcription. It can help get the following from your audio.

- [Speaker diarization](https://deepgram.com/product/speech-understanding/)
- [Language detection](https://deepgram.com/product/speech-understanding/)
- [Summarization](https://deepgram.com/product/speech-understanding/)
- [Topic detection](https://deepgram.com/product/speech-understanding/)
- [Language translation](https://deepgram.com/product/speech-understanding/)
- [Sentiment analysis](https://deepgram.com/product/speech-understanding/)
- [Entity detection](https://deepgram.com/product/speech-understanding/)
- [Transcription](https://deepgram.com/product/transcription/)
- [Redaction](https://deepgram.com/product/transcription/)

## Create a Free Deepgram Account

Before you start, it's essential to generate a Deepgram API key to use in our starter applications. [Sign-up now for Deepgram](https://console.deepgram.com/signup).

## Issue Reporting

If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Security Policy](./SECURITY.md) details the procedure for contacting Deepgram.

## Author

[Deepgram](https://deepgram.com)

## License

This project is licensed under the MIT license. See the [LICENSE](./LICENSE) file for more info.
