# Zap Configuration Guide

This guide provides step-by-step instructions on how to configure the "One-Click Instant Feedback Collection" Zapier automation (Zap).

## Prerequisites

Before you start, make sure you have:

- A Zapier account.
- An IoT button like Flic or a virtual button in a mobile app that integrates with Zapier, already configured to trigger an action recognized by Zapier.
- An email account that can be used to send feedback forms.
- A feedback form hosted on a platform like Google Forms, Typeform, or SurveyMonkey.

## Step 1: Create a New Zap

1. Log in to your Zapier account.
2. Click on the "Make a Zap" button.
3. Name your Zap "One-Click Instant Feedback Collection".

## Step 2: Set Up Your Trigger

1. For the trigger app, select the app that corresponds to your button (e.g., Flic, IFTTT, Button Widget, Tasker).
2. Choose the trigger event that corresponds to the action you configured your button to perform (e.g., Button Pressed, HTTP request, webhook).
3. Follow the instructions to connect your button to Zapier, if not already done.

## Step 3: Set Up Your Action

1. For the action app, select your email platform (e.g., Gmail, Outlook).
2. Choose the action event "Send Email".
3. Connect your email account to Zapier, if not already done.
4. In the "To" field, enter the email addresses of the recipients or set up a dynamic field if the recipients are to be determined based on the meeting attendees.
5. In the "Subject" field, enter a subject line for the email.
6. In the "Body" field, enter the content of the email. You can include a personalized greeting, a brief explanation, and the link to the feedback form. For detailed instructions on how to customize the email content, refer to `Email_Template.md`.

## Step 4: Test Your Zap

1. Click on the "Test & Continue" button. This will send a test email to the recipients.
2. Check the recipients' inboxes to ensure they received the email and that the content is correct.
3. If everything is working correctly, click on the "Turn on Zap" button.

## Conclusion

Once you have completed these steps, your Zap should be ready to use. Whenever you press the button, it will trigger the Zap and send a feedback form to the designated recipient(s). If you encounter any issues, refer to `Troubleshooting_Guide.md`.
