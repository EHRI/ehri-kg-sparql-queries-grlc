# EHRI-KG SPARQL Queries for grlc

This repository contains SPARQL queries designed to create an OpenAPI using [grlc](https://grlc.io). The queries are tailored for the EHRI-KG (European Holocaust Research Infrastructure Knowledge Graph) and include endpoints for accessing information about countries, institutions, and archival descriptions.

## Overview

The EHRI-KG API provides structured access to Holocaust-related archival material held in institutions across Europe and beyond. This repository includes SPARQL queries that serve as the foundation for a REST API over the EHRI-KG and a test EHRI-KG MCP (Model Context Protocol) implementation.

## Queries Included

The repository includes the following SPARQL queries:

### Archival Descriptions
- `archival-description.rq`
- `archival-descriptions-count.rq`
- `search-archival-descriptions.rq`
- `institution-archival-descriptions.rq`
- `search-institution-archival-descriptions.rq`

### Countries
- `countries.rq`
- `countries-count.rq`
- `country.rq`
- `country-institutions.rq`
- `search-country.rq`
- `search-country-institutions.rq`

### Institutions
- `institutions-count.rq`
- `institution.rq`
- `search-institution.rq`

### General Search
- `general-search.rq`

## License

This repository is part of the EHRI-KG project. For licensing information, refer to the project's main repository or contact the maintainers.

## Contact

For questions or issues related to these queries, please refer to the EHRI-KG project documentation or contact the maintainers.
