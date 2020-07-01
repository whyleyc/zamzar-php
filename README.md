# zamzar-php

A simple PHP script to demonstrate usage of the [Zamzar file conversion API](https://developers.zamzar.com/). 

The script:

1. Uploads a file for conversion
2. Polls the API to verify if the conversion job has completed
3. Downloads any converted files when it has completed

## Prereqs

Make sure you have:

* A version of PHP >5.3 installed.
* [Registered for a Zamzar API account](https://developers.zamzar.com/pricing) and have a valid API key that you can use.

## Running the script

* Change the `YOUR_API_KEY` to use your Zamzar API key
* Modify `$sourceFilePath` to point to a file on your local filesystem you wish to convert
* Update `$convertedFilePath` to use a path on your local filesystem where you wish to save any converted files.
* Change `$targetFormat` to the name of a target format you wish to convert your file to ([check here](https://developers.zamzar.com/formats) for a full list of supported formats).
* Run the script from the command line using: `php zamzar-sample.php`

For further information check out the [Zamzar API docs here](https://developers.zamzar.com/docs).
