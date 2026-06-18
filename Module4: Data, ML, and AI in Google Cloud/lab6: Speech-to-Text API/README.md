# Speech-to-Text API: Qwik Start (GSP119)

## Objective
To learn how to use the Google Cloud Speech-to-Text API by creating an API key, preparing a request file, and sending audio data to receive a text transcription.

## Key Steps Performed
1. Enabled Speech-to-Text API in Google Cloud Console.
2. Created an API key with restricted access.
3. Connected to the provided Compute Engine VM using SSH.
4. Stored the API key as an environment variable.
5. Created a `request.json` file using nano editor.
6. Configured the request with:
   - Audio encoding: FLAC
   - Language: English (en-US)
   - Audio source: Cloud Storage URI
7. Used `curl` command to send a POST request to the Speech-to-Text API.
8. Received JSON response containing transcript and confidence score.
9. Saved API response into `result.json`.

## Tools / Services Used
- Google Speech-to-Text API
- Cloud Console (APIs & Services)
- Compute Engine VM (SSH)
- Cloud Shell
- curl
- JSON configuration file
- Cloud Storage audio file

## Results
Successfully sent an audio file to the Speech-to-Text API and received an accurate text transcription with confidence score. The API correctly converted speech audio into readable text.
