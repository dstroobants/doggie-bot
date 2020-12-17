# Doggie-bot WIP
Bot that notifies when new puppies/dogs are being added for sale on [dogs.ie](https://dogs.ie/)

1. Create a `config.env` file in the root directory and add your email address, name, [MailJet](https://www.mailjet.com/) api key and secret.

Example:
```
MAILJET_API_KEY=1234567890abcdefghijklmno
MAILJET_API_SECRET=1234567890abcdefghijklmno
EMAIL=youremail@gmail.com
NAME=yourname
SEARCH_URLS=['https://dogs.ie/dogs/golden-retriever/?filter=yes&breed=18&gender=&county=all&sort=','https://dogs.ie/dogs/springer-spaniel/?filter=yes&breed=45&gender=&county=all&sort=']
```
2. Run `make run`
