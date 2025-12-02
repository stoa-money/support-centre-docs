# Soft Rejection

## Soft Rejection Reasons

Please see below the following events which qualify as a "soft rejection":

* Nationality does not match nationality on ID document.
* Full legal name provided does not match one shown on ID document.

## Protocol

Do the following:

1. Reset user's Stoa ID by deleting it in the Clerk dashboard.
2. Revoke the user's active session by clicking 'Ban User' and 'Unban User' in the Clerk dashboard.
3. Send user email, using email template in HubSpot, informing them of the rejection reason and to restart their application – this time with the correct information (e.g., if user submitted United Kingdom as their nationality, ask that they submit an ID document that shows this). The email contains a link to sign in – when the user signs in, a new Stoa ID will be created for them.
4. Increment 'Application Restarted' contact property in HubSpot by 1.
