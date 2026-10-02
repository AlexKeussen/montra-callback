# montra-callback

Static redirect page for the Montra iOS app's bank sign-in (Enable Banking).
It forwards the query string it receives to the app's sign-in sheet
(`com.alexkeussen.montra:/oauth/callback`). No scripts from elsewhere, no
tracking, no storage. The code it forwards is single-use and cannot be
redeemed without Montra's private application key.
