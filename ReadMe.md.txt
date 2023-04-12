How to run postman collection using newman

1. Install newnam

2. cmd into the root folder of this test - API_Newman_testing

3. Then, execute this command:

newman run C:\Users\olatu\OneDrive\Desktop\API_LoadAutomation\APITestingWorkSpace\API_Newman_Testing\reqresAPI.postman_collection.json -e C:\Users\olatu\OneDrive\Desktop\API_LoadAutomation\APITestingWorkSpace\API_Newman_Testing\Url_reqresAPI.postman_environment.json


4. To run the collection with nth number of iterations (e.g 10), execute this command:

newman run C:\Users\olatu\OneDrive\Desktop\API_LoadAutomation\APITestingWorkSpace\API_Newman_Testing\reqresAPI.postman_collection.json -e C:\Users\olatu\OneDrive\Desktop\API_LoadAutomation\APITestingWorkSpace\API_Newman_Testing\Url_reqresAPI.postman_environment.json -n 10

Happy testing!