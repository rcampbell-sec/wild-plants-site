# tasks
## mongodb
✅ conn string -> env vars 

✅ flask app connect to db 

✅ read notes into python 

✅ model/view stuff!? [mongo alternative] 

⭕ input validation/sanitisation

✅ user model

## review all
✅ read from json array 

✅ display in nice grid 

✅ get thumb image to show 

✅ fix grid so it's more evenly distributed 

### view note overlay
✅ click on an existing note and see the full description and details?

## new note
✅ date picker 

✅ form submit 

✅ save array from tags 

✅ save to mongodb 

✅ photo upload 

✅ create thumbnail image with square ratio

    ⭕ doesn't seem to always crop - because of size perhaps?

⭕ error handling for picture file uploads

⭕ better handle 'success' eg nicer transition after new note created

⭕ make it PRETTIER

## edit note
✅ change any field value 

✅ delete 

⭕ confirmation for deletion

✅ remove image when deleting or changing! (notemodel)

⭕ remove attached image?

✅ see existing image on this screen


## user system
⭕ user login

⭕ user session

⭕ create user

⭕ retrieve user data

⭕ check for logged in, display "log in" or "sign up" or go straight to new note

```
import bcrypt
hashed_pw = bcrypt.hashpw(passphrase, bcrypt.gensalt())
if bcrypt.hashpw(testphrase.encode('utf-8'), hashed_pw) == hashed_pw:
    print("pw match")
```

## search system
⭕ tags

⭕ search by location??

⭕ filter(s) on review all screen

⭕ ordering results on review all