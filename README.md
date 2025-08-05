In this task,I have uploaded a sample phishing e-mail in the form of a text file.Through that file I come to know various outcomes regarding that E-mail:-
1. Sender’s Email Address (Spoofing Check)
The sender appears as “PayPal Support support@paypal-alerts.com”.
“PayPal” uses a capital “L” instead of a lowercase “l” which is a visual spoof.
The domain “paypal-alerts.com” is NOT an official PayPal domain.

2. Email Header Check (with Online Header Analyzer)
I had analyzed Sender's Email's Header by Online Header Analyzer tool which reveals:
    If the “From” domain differs from the actual sender domain.
    Discrepancies between “Reply-To,” “Return-Path,” and “From” addresses.
    IP addresses or server relay paths not associated with PayPal.
    If the header shows the message came via a non-PayPal mailserver, that’s a spam.
Also I had uploaded screenshot regarding this Email Header check labeled as header_analyzer1,2,3,4,5,6 in this repository.

4. Suspicious Links and Attachments
The email contains a link which is labeled as “Confirm Your Account” whic will redirect the user to “http://safety-paypal-support.com/user-login” which is not an official PayPal login URL.Thus this was removed from the website earlier.Here When a user enters their User ID and Password then it is captured by the spammer which can misuse it.Also phishing emails often include dangerous files (PDFs, DOCX, ZIP) which can be very malicious.

5. Urgent/Threatening Language
Phrases like “avoid suspension,” “Failure to comply within 24 hours will result in permanent account closure,” and urging “immediate action" indicates most commonly used phishing tactics.

6. Mismatched URLs 
Hovering over the “Confirm Your Account” link reveals the true destination (“http://safety-paypal-support.com…”), mismatched from legitimate PayPal URLs.This is a mismatch between visible link text and actual URL generally showing a confirm sign of phishing.

7. Spelling or Grammar Errors
“Dear Customer” is a generic greeting.Instead of this there should be name of the user of paypal.
Subtle grammatical oddities (overly formal closing, no customer name, awkward syntax—“Failure to comply within 24 hours…”).
Some phishing emails include blatant typos or odd phrasing to bypass spam filters

7.Summary
Spoofed sender address-paypaI” with a capital “I”, fake domain
Header discrepancies-Sender domain/IP won’t match PayPal
Suspicious links/attachments-Fake link to non-PayPal site
Urgent/threatening language-24-hour deadline, account suspension threat,immediate action
Mismatched URLs-Hover reveals suspicious URL
Spelling/Grammar errors-Generic greeting, slight awkwardness etc...
bypassing spam filters common techniques-Blatant typos and odd phrasing.
