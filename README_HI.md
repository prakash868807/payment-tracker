# Payment Record Website

यह Flask + SQLite website है।

## Local computer पर चलाने के लिए
1. Python install करें।
2. Terminal में इस folder में जाएँ।
3. `pip install -r requirements.txt`
4. `python app.py`
5. Browser में `http://127.0.0.1:5000` खोलें।

Default admin password: `admin123`

Production में `ADMIN_PASSWORD` और `SECRET_KEY` environment variables बदलना जरूरी है।

## Excel format
पहली row:
`Name | Amount | Date | Note`

बाकी rows में payment data।

## Online link
इसे किसी Python-compatible hosting service पर deploy करना होगा। Public link मिलने के बाद वही link group में भेज सकते हैं। Database को persistent storage के साथ configure करना जरूरी है ताकि restart के बाद data न मिटे।
