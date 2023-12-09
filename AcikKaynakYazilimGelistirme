import requests

url = 'https://jsonplaceholder.typicode.com/todos/1'

try:
	response = requests.get(url)

	response.raise_for_status()

	data = response.json()

	print(data)

except requests.exceptions.RequestException as err:

	print(f'Hata oluştu: {err}')

