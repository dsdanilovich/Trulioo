POST /verifications/v1/verify HTTP/1.1
Host: api.globaldatacompany.com
Content-Type: application/json
Authorization: Basic RGVsdGVjX0RlbW9fQVBJIDpEZWx0ZWNAMjAxOEVV
Cache-Control: no-cache
Postman-Token: 66f95579-8805-41b7-b45e-d6520cbf0750

{
  "AcceptTruliooTermsAndConditions": true,
  "CleansedAddress": false,
  "VerboseMode": true,
  "ConfigurationName": "Identity Verification",
  "CountryCode": "BE",
  "DataFields": {
    "PersonInfo": {
      "FirstGivenName": "Luis",
      "FirstSurName": "Santer",
      "DayOfBirth": "12",
      "MonthOfBirth": "12",
      "YearOfBirth": "1978"
    },
    "Location": {
      "PostalCode": "1930"
    },
    "Business": {}
  }
}
