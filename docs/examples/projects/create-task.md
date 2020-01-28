from appwrite.client import Client
from appwrite.services.projects import Projects

client = Client()

(client
  .set_project('')
  .set_key('')
)

projects = Projects(client)

result = projects.create_task('[PROJECT_ID]', '[NAME]', 'play', '', 0, 'GET', 'https://example.com')