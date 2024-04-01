API client with authorisation

sample call: 

url = 'https://api.sampleapis.com/beers/ale'
url_auth = ''
login = ''
password = ''

api = ApiFirst(url, url_auth, login, password)
json, status = api.get()
print(status)
print(json)

if code start '2' - you get answer
if code not '2' - toy get generated json with code
if code '401' - func get new api key and save to file

