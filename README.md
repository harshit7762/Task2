In this task,I have uploaded a sample phishing e-mail in the form of a text file.Through that file I come to know various outcomes regarding that E-mail:-
1. Sender’s Email Address (Spoofing Check)
The sender appears as “PayPal Support support@paypal-alerts.com”.
“PayPal” uses a capital “L” instead of a lowercase “l” which is a visual spoof.
The domain “paypal-alerts.com” is NOT an official PayPal domain.

2. Email Header Check (with Online Header Analyzer)
Analyzing email headers using tools like Zoho Toolkit or mailheader.org can reveal:
    If the “From” domain differs from the actual sender domain.
    Discrepancies between “Reply-To,” “Return-Path,” and “From” addresses.
    IP addresses or server relay paths not associated with PayPal.
    If the header shows the message came via a non-PayPal mailserver, that’s a spam.
