## 0.41

Use the same JWT library instead of using two different ones.

Add Description() for Alert bodies.

## 0.40

Fix next page URL's for Twilio Monitor

## 0.39

The data in Update() requests was silently being ignored. They are not ignored
any more.

Support the Accounts resource.

Add RequestOnBehalfOf function to make requests on behalf of a subaccount.

Fixes short tests that were broken in 0.38

## 0.37

Support Outgoing Caller ID's

## 0.36

Support Keys

## 0.35

Added Ended(), EndedUnsuccessfully() helpers to a Call, and FriendlyPrice() to
a Transcription.