# Emailer
Excel based Email Sender
# Email Sender

This code allows you to send personalized emails to multiple recipients using the Yagmail library in Python. It reads email addresses and names from an Excel spreadsheet, iterates over the rows, and sends the emails individually.

## Prerequisites

Before running this code, ensure that you have the following:

1. **Pandas**: Install the Pandas library using the following command:

   ```
   pip install pandas
   ```

2. **Yagmail**: Install the Yagmail library using the following command:

   ```
   pip install yagmail
   ```

3. **Excel Spreadsheet**: Prepare an Excel spreadsheet with the email addresses and corresponding names. Make sure the file path is correctly specified in the code.

## Setup

1. Clone the repository and navigate to the project directory.

   ```
   git clone https://github.com/your-username/email-sender.git
   cd email-sender
   ```

2. Install the required dependencies using pip.

   ```
   pip install -r requirements.txt
   ```

3. Open the `email_sender.py` file in a text editor.

4. Replace the following placeholders with your email credentials:

   - Replace `'email address'` with your email address within the `yagmail.SMTP` initialization.
   - Replace `'in app password'` with your email's app password within the `yagmail.SMTP` initialization. Note that app passwords are used for email clients with two-factor authentication enabled.

5. Customize the subject and body of the email:

   - Replace `'Add the subject here'` with your desired subject within the `subject` variable.
   - Replace `'Add the body of text here. Substitute \n for line breaks.'` with the desired content of the email within the `body` variable. You can use string formatting to personalize the email content, as shown in the example.

## Usage

1. Place the Excel spreadsheet with email addresses and names in the specified file path (`C:/Users/User/Downloads/TestEmail.xlsx` in this case).

2. Run the `email_sender.py` file.

   ```
   python email_sender.py
   ```

3. The code will read the spreadsheet, iterate over the rows, and send personalized emails to each recipient.

4. The SMTP connection will be closed automatically after sending all the emails.

## License

This code is released under the MIT License. Feel free to modify, distribute, and use it as per your requirements.

If you have any questions or suggestions, please feel free to reach out. Happy emailing!
