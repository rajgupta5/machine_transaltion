# machine_transaltion

- Create a new environment
- Install all packages from requirement.txt
- Run main.py
- From Postman run below request

Request:

curl -X POST \
  http://localhost:8000/predict \
  -H 'Content-Type: application/json' \
  -H 'Postman-Token: 3832876e-e3e2-4be5-a75c-4bd38bb69921' \
  -H 'cache-control: no-cache' \
  -d '{
	"text": "I am going to beach today"
}'

Responnse:

{
    "Result": "मैं आज समुद्र तट जा रहा हूं"
}
