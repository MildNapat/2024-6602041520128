Invoke-RestMethod -Uri "http://localhost:8080/api/auth/local/register"  
-Method Post  
-Headers @
{ "Content-Type" = "application/json"; 
"Authorization" = "Bearer f55a725cb31eaae91a9fe9ac52cb803640b5fcd405c1a1b5ed711b87830fbda7c740542fbbf9c01dd6f30592c811a34327786887d2cf67d665257029e2a51b0822b06ed3db0a6b257dfef98b4eb6e9243942a73b9568703d103d125c373fe3d6cf339ccaa437e0503ee1bea032204fd6176414df4ae7138bed2e9384b7fd226f" }  
-Body '{ "username": "napat555", 
"email": "napat33@gmail.com", 
"password": "P@ssw0rd" }'
