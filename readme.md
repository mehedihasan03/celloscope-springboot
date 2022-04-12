	curl --location --request POST 'http://localhost:8787/api/v1/user/save' \
	--header 'Content-Type: application/json' \
	--data-raw '{
	    "id" : 1,
	    "userId" : "mehedi01",
	    "password" : "123",
	    "mobile" : "01835233447"
	}'
