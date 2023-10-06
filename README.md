# Create Invoice («Faktura anlegen»)

## Goal of this repository

The repository "Create Invoice" is focused on the creation of invoices (Faktura) within the ERP system. It encompasses various billing documents, including invoices, credits, debits, cancellations, and more. This repository offers the essential tools and interfaces to streamline the invoicing process, ensuring the efficient generation and management of invoices in line with the business's financial demands.

Blending automated and manual functionalities, it equips technical users with the capability to customize their invoicing workflow to match their distinct needs and preferences.

For more insights, refer to [Create Invoice](https://help.sap.com/docs/SAP_ERP/3c8204a4aeba432a863131243594c715/da24c0534b22b64ce10000000a174cb4.html?version=6.05.latest).

For a deeper understanding of the definition, usage, structure, and integration of Faktura, see [Faktura](https://help.sap.com/docs/SAP_ERP/3c8204a4aeba432a863131243594c715/7269b753128eb44ce10000000a174cb4.html?version=6.05.latest).

## How does this API work?

Multiple links to the official SAP documentation will guide you in grasping the various parameters and essential information required to utilize the API effectively.

- **Billing Document – Create**: 
  Users of this inbound service can generate billing documents in your system by transmitting billable data via SOAP messages. This facilitates billing data from external systems (e.g., orders and deliveries crafted in a non-SAP system) to be invoiced within your system.
  [More details](https://api.sap.com/api/BILLINGDOCUMENTREQUEST_IN/overview)

- **Billing Document Request – Create**: 
  Users of this inbound service can establish billing document requests in your system by dispatching billable data through SOAP messages. Billing document requests comprise a header and one or more billing items. Storing external billing data as billing document requests (instead of directly inputting the data into billing document creation) allows billing data from various internal and external sources to merge into a singular, consolidated billing document.
  [More details](https://api.sap.com/api/BDR_REQUEST_IN/overview)

- **Billing Document – Send Creation Confirmation**: 
  For each request to produce billing documents received via the inbound service "Billing Document - Create," this outbound service response confirms the successful creation of billing documents. If the system couldn't generate specific billing documents or billing items, the service elucidates the reasons for the failure.
  [More details](https://api.sap.com/api/CO_SDBIL_ESR_BD_CONF_OUT/overview)

## Contact information

From the details provided above, you should attain a comprehensive overview of the API's capabilities.

If you're keen on using and collaborating with the API, please reach out so we can assess your application and supply the necessary credentials and details.

For additional support with the API, the BIT technical support SAP team is on standby to address your inquiries during regular business hours.

To get in touch, please email [FachsupportSAP@bit.admin.ch](mailto:FachsupportSAP@bit.admin.ch).
