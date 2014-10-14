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