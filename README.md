# OTP-Verification-System-in-Python
Python scripting, email handling, and real-world OTP systems which are widely used in authentication systems.
What I built:

1. A system that generates a secure 6-digit OTP
2. Sends the OTP to the user’s email for verification
3. User enters the OTP and system verifies it
4. Provides 3 retry attempts in case of wrong OTP
5. Handles errors gracefully (like email sending failure)

📚 Libraries & Tools I used:

random → to generate 6-digit OTP

smtplib & ssl → to send emails via Gmail SMTP

email.mime (MIMEText, MIMEMultipart) → to format email (plain + HTML)

input() handling → for user OTP entry and validation
