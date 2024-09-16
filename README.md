# Insecure access to user tokens data in MFASOFT Secure Authentication Server 1.8.x through 1.9.x before 1.9.040924
Vulnerability, allows you to view data about user tokens without authentication (IDOR) on the endpoint “/api-selfportal/get-info-token-properties” by brute-forcing the “serial” parameter. The search was carried out using the code GA0000NUM
