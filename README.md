# SQLi Exploiter

WARNING: This is not a script kiddie tool! Usage requires detailed knowledge of the vulnerability, a thorough understand of the functionality available in the affected RDBMS, and the ability to write Python. The good news is that it is highly configurable.

Born out of a need to exploit SQL injection vulnerabilities that sqlmap just couldn't find. Always try sqlmap first. It is highly customizable and only fails in very complicated injection scenarios. However, when it does fail, use this. Enjoy!

 \- Tim (@lanmaster53) Tomes

## Getting Started

1. Install the dependencies: `pip install -r REQUIREMENTS.txt`
2. Edit the `config.py` file and follow the numbered configuration steps.
3. Run the script: `python ./sqli-exploiter.py`

Developed and tested in Python 3, but may also work in Python 2. I have no idea...
