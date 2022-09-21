Staticrypt is available through npm as a CLI, install with npm install -g staticrypt (with or without the -g flag).

Encrypt test.html and create a test_encrypted.html file (add -o my_encrypted_file.html to change the name of the output file):

```
staticrypt index.html 123 --title="VI Дальневосточная конференция МАКМАХ по антимикробной терапии и клинической микробиологии" --output="./docs/index.html" --file-template="./password_template.html" --config  --decrypt-button="Показать" --remember="Запомнить меня" --passphrase-placeholder="Пароль" --remember-label="Запомнить меня"  
```

More info: https://www.npmjs.com/package/staticrypt

