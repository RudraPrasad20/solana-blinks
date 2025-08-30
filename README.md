## expoloring solana blinks

# GET

send get request to:
http://localhost:3000/api/actions/memo

# POST

send post request to :
http://localhost:3000/api/actions/memo
with raw body:
{
"account": "YOUR PUB KEY"
}

- you will get an transaction in return
- GET request returns metadata
- POST request returns a signable transaction
