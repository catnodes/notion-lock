# notion-lock

Simple add-on for Notion that encrypts and decrypts plain text using a password.
It uses AES encryption in Browser, no data is send to any server during encryption or decryption. All runs locally on your machine memory ;D

It is only possible to recover the data by typing the text and the correct password used to encrypt the data. 
This allows for multiple passwords to be used for different text.

# How-to

## Adding it to notion

1. Add the URL https://catnodes.github.io/notion-lock as an embedded view on any page of Notion.
2. Resize the frame to your liking.
3. you are done! =D

## Encrypt text

1. Type a password or passfrase to encrypt your data, you must remember this password and type exactly it in order to recover (decrypt)
2. Type the text you wish to encrypt
3. Choose the checkbox "Encrypt text"
4. Press the blue buttom "Generate text"
5. Copy the text below Result, this is your encrypted data, or press the buttom "Copy to Clipboard"
6. Save the text anywhere you wish on Notion

## Decrypt text

1. Type the password or passfrase you used to encrypt your text
2. Copy the encrypted text to the textarea field
3. Choose the checkbox "Decrypt"
4. Press the green button "Generate Text"
5. Thats it! Your secret data is now available to you!

# Afraid of me deleting this repo?

Some users have reached me out asking how relaiable their sensitive data is store since this is a public project hosted on github pages. I can´t garantee that this repo will live forever nor github pages will always be working. 

To solve the issue of me deleting this repo, although I have no intention in doing it, you can always fork this repo. You will have it on your github account, and then you can set up github pages on your forked project. This negates the possibility of me deleting the repo. 

Here is a how to setup github pages on a projec in case you don´t know how: [Quickstart for Github Pages](https://docs.github.com/en/pages/quickstart)

The script is all in one single index.html file as well, so if you happen to have a hosting service, you can put it in there and avoid depending on github pages.

#### Disclaimer: The add-on uses AES encryption in Browser, no data is send to any server during encryption or decryption. It runs local on your machine memory !! There is no way to recover data stored if you lose your password.
