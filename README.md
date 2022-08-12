# Email-Notification-Trigger-from-Google-Spreadsheet-Using-Google-Apps-Script

### Remark
Create an email template. In your Gmail account, create an email draft. To include data from the spreadsheet in your email, use placeholders that correspond to column names surrounded by curly braces, such as {{First name}}. Copy the subject line of your email draft.

### Example:

        Subject: Automatic Email Notification - New Tender has been uploaded

        Dear Commercial Department,

        Please click to the link below for more information on the tender:

        Tender No.: {{No. Tender}}
        Tender Title: {{Tajuk}}
        Tender url: {{Pautan}}
        Ministry: {{Kementerian}}
        Agency: {{Agensi}}
        Field Code: {{Kod Bidang}}
        Start Date: {{Tarikh mula}}
        End Date: {{Tarikh akhir}}

        Thank you and best regards,
        Analytics Department
