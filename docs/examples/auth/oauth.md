from appwrite.client import Client
from appwrite.services.auth import Auth

client = Client()

(client
  .set_project('')
  .set_key('')
)

auth = Auth(client)

result = auth.oauth('bitbucket', 'https://example.com', 'https://example.com')