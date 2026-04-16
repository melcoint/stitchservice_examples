# Running Examples

This guide explains how to set up and run the provided examples.

## Prerequisites

* Access to Melco Cloud account
* API Key from Melco Cloud
* Git (optional, if cloning the repository)

## Setup Instructions

### 1. Download or Clone the Repository

You can either:

* Download the required **environment** and **collection** files manually, or
* Clone the repository using Git:

```bash
git clone <repository-url>
cd <repository-folder>
```

### 2. Configure API Key

1. Open the environment file.
2. Locate the following variable:

```
API_KEY
```

3. Replace its value with your API key.

   * You can obtain your API key from your Melco Cloud account.

## Running the Examples

* Import the collection and environment files into your API client (e.g., Postman).
* Ensure the correct environment is selected.
* Execute the requests in the collection.

## Notes

* Make sure your API key is kept secure and not shared publicly.
* Verify that all environment variables are correctly configured before running requests.
