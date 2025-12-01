# Soft Rejection

## Soft Rejection Reasons

Please see below the following events which qualify as a "soft rejection":

* Nationality does not match nationality on ID document.
* Full legal name provided does not match one shown on ID document.

## Protocol

Do the following:

1. Reset user's Stoa ID by deleting it in the Clerk dashboard.
2. Send user email, using email template in HubSpot, informing them of the rejection reason and to restart their application – this time with the correct information (e.g., if user submitted United Kingdom as their nationality, ask that they submit an ID document that shows this).
3. Increment 'Application Restarted' contact property in HubSpot by 1.
