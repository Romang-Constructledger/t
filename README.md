# t

A one-page forwarder for NFC tags. A tag link looks like `https://romang-constructledger.github.io/t/?i=A01`.
The page checks that `i` is one capital letter and two digits, then forwards to a private page that only
its owner can open. Anything else shows "Unknown tag."

It makes no other network requests, keeps no data, and sets no cookies. Its Content-Security-Policy
allows only its own inline script and style.
