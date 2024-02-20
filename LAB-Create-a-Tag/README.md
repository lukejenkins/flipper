# LAB: Create a tag

The objective of this lab is to create an NFC tag from scratch. We will be making a tag that when scanned with a phone will prompt a user to visit a specific website.

First, navigate to the Apps view:

![.](./screenshots/Screenshot-20240219-153035.png)

Then navigate to the NFC folder:

![.](./screenshots/Screenshot-20240219-153047.png)

And select the NFC Maker app:

![.](./screenshots/Screenshot-20240219-153056.png)

This app lets you create many different types of NFC tags, but we want to create a non-SSL URL, so we select "Plain URL":

![.](./screenshots/Screenshot-20240219-170329.png)

On the next screen we type in the URL we want to program to the tag. Note that if you do not want to use SSL, you have to scroll back to the beginning of the URL screen and remove the "s" in "https":

![.](./screenshots/Screenshot-20240219-170126.png)

Hit "save" and then either give the tag a memorable name, or take note of the auto-generated name:

![.](./screenshots/Screenshot-20240219-170136.png)

We should get a thumbs up for a well-saved tag:

![.](./screenshots/Screenshot-20240219-153234.png)

Now we go into the main "NFC" app:

![.](./screenshots/Screenshot-20240219-153308.png)

And select the "saved" option:

![.](./screenshots/Screenshot-20240219-153316.png)

And open up the tag we just created:

![.](./screenshots/Screenshot-20240219-170222.png)

And select "write":

![.](./screenshots/Screenshot-20240219-153848.png)

Put your flipper next to an NTAG215 which is writable:

![.](./screenshots/Screenshot-20240219-153855.png)

Good job!

![.](./screenshots/Screenshot-20240219-153999.png)

If you read it again with the NFC app, this is what it looks for:

![.](./screenshots/Screenshot-20240219-171846.png)
