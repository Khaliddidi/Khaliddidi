import requests

 def get_match_result(home_team, away_team, match_date, league):
    fake_api_url = "https://fake-sports-api.com/match_result"
    params{"home_team": home_team,
        "away_team": away_team,
        "match_date": match_date,
        "league": league }
        response = requests.get(fake_api_url, params=params)
    if response.status_code == 200:
        result = response.json()
        return resul
       home_team = input("home_team:")
away_team = input("away_team: ")
match_date = input("match_date): ")
league = input("league:")



