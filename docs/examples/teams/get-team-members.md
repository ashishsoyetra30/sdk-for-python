from appwrite.client import Client
from appwrite.services.teams import Teams

client = Client()

(client
  .set_project('')
  .set_key('')
)

teams = Teams(client)

result = teams.get_team_members('[TEAM_ID]')