# Secure Coding

A small Flask app for a secure coding course. It is **intentionally insecure**: it shows common web vulnerabilities, like stored XSS in comments, CSRF on money transfers, and plaintext password checks, with TODOs marking how to fix each one.

Don't deploy it. The assignment is in `Secure_Coding.pdf`.

## Run it

```bash
cd Secure_App
pip install -r requirements.txt
python init_db.py
python routes.py
```
