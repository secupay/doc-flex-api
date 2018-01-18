doc-flex-api
============

| Document | Description
| ----- | ------
| [secupay API-flexv2_de.pdf](docs/secupay API-flexv2_de.pdf) | german API description
| [secupay API-flexv2_en.pdf](docs/secupay API-flexv2_en.pdf) | english API description

## The secupay Flex API (flex.API) for processing online payments

The secupay Flex API, subsequent named flex.API, is roughly a REST Interface. Therefor its fairly easy to use via https requests.
The hostname of the api is api.secupay.ag, the protocol is https, which leads to the following base url for request:

https://api.secupay.ag/

For safety reasons only port 443/https is allowed on the api host, you can not use port 80, such requests will get rewritten to port 443.
For initial development, you should use our dist system. This ensures clean separation between development and productive environments. 
Additionally no transactions are getting charged and there is no cost for any request.

https://api-dist.secupay-ag.de

## API key
[Please contact the secupay Customer Service for an API key.] (https://www.secupay.ag/integrationscenter)

## Payment state diagram
![payment state diagram](https://www.lucidchart.com/publicSegments/view/1365d9d7-41b8-4ab9-8c9a-65c4eb8d9c64/image.png)

### Prepay
![prepay state diagram](https://www.lucidchart.com/publicSegments/view/833667a7-1db6-434d-be42-d8ebd8f9d480/image.png?v=1)

### Debit
![debit state diagram](https://www.lucidchart.com/publicSegments/view/c85da5c0-9b84-4795-a3d3-478eb3468de6/image.png?v=1)
