# Secure Coding

Tutorial material: a small Flask app that is **intentionally insecure**: it shows common web vulnerabilities, like stored XSS in comments, CSRF on money transfers, and plaintext password checks, with TODOs marking how to fix each one.

Don't deploy it. The tutorial requirements are in `Secure_Coding.pdf`.

## Run it

```bash
cd Secure_App
pip install -r requirements.txt
python init_db.py
python routes.py
```
