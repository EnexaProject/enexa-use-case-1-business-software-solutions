<div style="display: flex; justify-content: space-between; align-items: center;">
  <h1>ENEXA use case 1: Business software solutions</h1>
  <img src="doc/datev.png" alt="Logo" style="width: 60px; height: 60px;">
</div>


## Ontologies

### The FiBu Ontology
Public version of the financial accounting domain, covering the entities Invoice, Posting, and Company (in context posting entity and business partner).
- [ttl-file](ontology/public_ACS_fibu_ontology.ttl)
- [WebVowl visualization](https://service.tib.eu/webvowl/#iri=https://raw.githubusercontent.com/EnexaProject/enexa-use-case-1-business-software-solutions/refs/heads/main/ontology/public_ACS_fibu_ontology.ttl)

### The Accounts of SKR03 Taxonomy
Taxonomy of all accounts included in the Standard Chart of Accounts (SKR) 03, version of 2023. The accounts are modelled as rdfs:subClassOf of fibu:Buchungskonto (i.e. posting account). 
- [ttl-file](ontology/public_accounts_skr3.ttl)

The SKR is a comprehensive list of accounts used to systematically record and categorize financial transactions. SKR03 contains predefined categories such as asset and capital accounts (0), financial and private accounts (1), accrual accounts (2), goods receipt and inventory accounts (3), operating expenses (4), inventories of products (7), revenue accounts (8), and carryforward and statistical accounts (9).
More recent versions of SKR can be downloaded as a PDF from [link](https://www.datev.de/web/de/datev-shop/material/kontenrahmen-datev-skr-03/).


