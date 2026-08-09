# CKL — Wholesale Portal (web client)

The browser-side of the CKL ordering portal, served as one self-contained file.

This repository is public because a web client is public by definition: every
browser that opens the portal downloads this file in full. Nothing secret lives
here.

* No credentials, PINs or customer data.
* No prices or stock — those are calculated and enforced on the server.
* The client sends intent only (article, colour, size, quantity) and a session
  token issued by the server.

Server code, business data and access control live in a separate private
repository and in a Google Sheet that only CKL staff can open.
