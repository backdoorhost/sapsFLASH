# sapsFLASH
South African Police Service Firearms License Resolver

sapsFLASH is a service that retrieves firearms license details for the South African Police Service. The API accepts a JSON payload and returns license details in JSON format.

## Payload Format
```json
{
  "token": "some-token-value",
  "idInst": "some-id",
  "ref": "some-ref",
  "serial": "some-serial"
}
```

## Response
On success, the API responds with the license details structured as follows:
```json
{
  "status": 200,
  "message": "Data retrieved successfully.",
  "data": {
    "applicationNumber": "some-application-number",
    "idInstNumber": "some-id",
    "serialNumber": "some-serial",
    "applicationType": "some-application-type",
    "caliber": "some-caliber",
    "make": "some-make",
    "statusDate": "YYYY/MM/DD",
    "applicationStatus": "some-status",
    "statusDescription": "some-description",
    "nextStep": "some-next-step"
  }
}
```

## Obtaining an API Token
To access this API, you must obtain a token. Contact me to request one.

## Usage
Include your API token in the request by replacing the "token" value with yours.

## License
This project is proprietary. All rights reserved.
For further licensing details, please refer to the accompanying LICENSE file or contact the project owner.

## Contact
x.com/secvoidnull
