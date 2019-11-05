# Read Write Google Spreatsheets

This is a simple vanilla PHP script that allow you to read, write a Google spreadsheet in your drive.

#### Usage

I will try to be as simple as possible. Lol

1. Clone this repo

    `$ git clone https://github.com/PaulinhoNdegwa/ReadWriteGooglesheets.git`

2. Get credentials to access and edit the spreadsheet
    - Go to the Google APIs Console
    - Create a new project.
    - Click `Enable API`. Search for and enable the `Google Drive API`.
    - Create credentials for a `Web Server` to access `Application Data`.
    - Name the `service` account and grant it a `Project Role of Editor`.
    - Download the JSON file.
    - Copy the JSON file to your app directory and rename it to `client_secret.json`

3. Collect the **client email** in the `client_secret.json ` allow it to access your spreadsheet
    - Open your spreadsheet, click on share and paste the email. Click **Send**

4. Edit the `readwritesheets.php` file with the name of the spreadsheet you want to access
    - The name must be of a sheet on your google drive

5. Run the script

    `$ php readwritesheets.php`

For the complete tutorial, visit this [link](https://www.twilio.com/blog/2017/03/google-spreadsheets-and-php.html)

Thank you!