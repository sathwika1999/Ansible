# Ansible
Converting the markdown meeting notes in python into Google Docs.

# Markdown to Google Doc Converter

This project converts markdown meeting notes into a well-formatted Google Doc using Python and the Google Docs API. It is designed to run in Google Collab and automates the process of creating structured meeting notes.


## Setup Instructions

1. **Enable Google Docs API**:
   - Go to the [Google Cloud Console](https://console.cloud.google.com/).
   - Create a new project or use an existing one.
   - Enable the **Google Docs API** and **Google Drive API**.
   - Create OAuth 2.0 credentials and download the `credentials.json` file.

2. **Upload Credentials to Collab**:
   - Open the `markdown_to_google_doc.ipynb` notebook in Google Colab.
   - Upload the `credentials.json` file to the Colab environment.

3. **Install Dependencies**:
   - Run the following command in a Collab cell to install the required libraries:
     ```bash
     !pip install google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client
     ```

4. **Run the Script**:
   - Execute the cells in the notebook to authenticate, parse the markdown content, and create the Google Doc.
