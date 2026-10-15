# Bali Travel Brief v66 — Protected Rooming & Flight Manifest

- Rooming List requires password authentication before names appear.
- Flight manifests require the same password before names and booking codes appear.
- Sensitive data is AES-GCM encrypted inside the HTML and decrypted locally in the browser.
- Password is not stored as plaintext in the HTML.
- Unlock lasts only until the page is reloaded/closed.
