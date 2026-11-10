# Privacy Policy

**Application:** Hermes Agent (personal Gmail integration)
**Owner:** josephdeveloperlgt (independent developer, Nairobi, Kenya)
**Last updated:** 10 November 2026
**Contact:** josephdeveloper2104@gmail.com

## 1. What this application is

Hermes Agent is a personal, single-user automation tool. It is not a public
service and has no other users. It is operated by, and on behalf of, its owner,
who is the sole holder of every Google account it is authorized against.

## 2. What data it accesses

With the owner's explicit consent, the application uses Google OAuth to:

- read and search Gmail messages in the owner's own mailboxes (scope
  `gmail.readonly`);
- send email from those mailboxes on the owner's instruction
  (scope `gmail.send`);
- apply labels and mark messages as read or unread (scope `gmail.modify`).

It does not access Google Calendar, Drive, Contacts, or any other Google service.

## 3. Where data is stored

OAuth access and refresh tokens are stored **only on the owner's own computer**,
in local files owned by the operating-system user account. There is no server
operated by this application and no central database.

Message content is processed in memory to answer the owner's requests. It is
written to a local file only when the owner explicitly asks for a document,
report, or export.

## 4. Sharing

No Gmail data is sold, rented, published, or shared with third parties. The only
external services involved are:

- **Google's Gmail API**, to read and send mail;
- **the AI model provider configured by the owner** in their own Hermes
  installation, to which excerpts of messages may be sent when the owner asks
  for summaries, drafts, or triage.

## 5. Retention and deletion

Tokens remain until the owner revokes them. The owner can revoke access at any
time at <https://myaccount.google.com/permissions> (Google Account → Security →
Third-party apps) and by deleting the local token files. Revocation takes effect
immediately for new requests.

## 6. Security

Tokens never leave the owner's machine except when transmitted directly to
Google's OAuth and Gmail endpoints over HTTPS. No credential is embedded in this
document or in any public repository.

## 7. Changes

Any change to this policy will be committed to this repository before the
application behaves differently.
