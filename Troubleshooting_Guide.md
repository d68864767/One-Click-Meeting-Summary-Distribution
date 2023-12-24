# Troubleshooting Guide

This guide provides solutions to common issues you may encounter while setting up and using the "One-Click Instant Feedback Collection" Zapier automation (Zap).

## Button Not Triggering the Zap

If pressing the button does not trigger the Zap:

1. Check the button's connection to your device. If you're using an IoT button, make sure it's paired with your device via Bluetooth. If you're using a virtual button, ensure the app is running and has the necessary permissions.
2. Verify that the button is correctly configured to trigger an action recognized by Zapier. Refer to `Button_Configuration.md` for detailed instructions.
3. In Zapier, check that the button press is set as the trigger for the Zap. Refer to `Zap_Configuration.md` for more information.

## Feedback Form Not Sent

If the feedback form is not sent when the button is pressed:

1. Check your email account settings in Zapier. Make sure Zapier has the necessary permissions to send emails from your account.
2. Verify that the email or message content is correctly configured in Zapier. It should include a link to the feedback form. Refer to `Email_Template.md` for detailed instructions.
3. Ensure the recipient's email address is correctly entered in Zapier. If the recipient is dynamically determined, check the logic used for this.

## Feedback Form Not Received

If the recipient does not receive the feedback form:

1. Ask the recipient to check their spam or junk mail folder. The email may have been incorrectly marked as spam.
2. Verify that the recipient's email address is correctly entered in Zapier. If the recipient is dynamically determined, check the logic used for this.
3. Check your email account settings in Zapier. Make sure Zapier has the necessary permissions to send emails from your account.

## Feedback Form Link Not Working

If the link to the feedback form does not work:

1. Check the link to the feedback form in your email or message template. It should be a direct link to the form.
2. Verify that the feedback form is correctly set up and published. Refer to `Feedback_Form_Guide.md` for detailed instructions.

Remember, thorough testing is crucial to ensure the Zap works correctly. If you encounter any other issues, refer back to the setup guides or contact Zapier support.
