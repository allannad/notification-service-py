# Credits, Notes, and Reference

## Sendgrid Transactional Emails

  + https://sendgrid.com/docs/ui/sending-email/how-to-send-an-email-with-dynamic-transactional-templates/
  + https://sendgrid.com/docs/for-developers/sending-email/using-handlebars/#iterations
  + https://sendgrid.com/dynamic_templates/


Setup:

```sh
conda activate emails-env

pip install python-dotenv
pip install sendgrid==6.0.5

python app/send_receipt.py
```

  + https://github.com/sendgrid/sendgrid-python
  + https://github.com/sendgrid/sendgrid-python/releases/tag/v6.0.0