# Source registry

Provider documentation reviewed in November 2026. Access varies by host, account and record.

Select sources for subject, language coverage, access and expected yield. This release uses host-provided search and page retrieval, with no bundled database connectors, API clients, credentials, or browser automation. A direct search means a query submitted to the provider's own interface or an authorized provider connector. A general web query limited to a provider's domain is indirect discovery. A retrieved publisher or catalog record can verify a candidate without implying direct search.

## International academic databases and publishers

| Source | When to use it and what access to expect |
| --- | --- |
| [JSTOR](https://www.jstor.org/) | Humanities journals, books and older scholarship. Public search and metadata, with open, account-limited and subscribed full text depending on the item. [Search and access guidance](https://support.jstor.org/hc/en-us/articles/4405598751255-Searching-Using-Filters-and-Facets) |
| [Project MUSE](https://muse.jhu.edu/) | Humanities journals and scholarly books. Use public search or indexed records. Full text depends on open access, purchase or institutional holdings. [Search help](https://about.muse.jhu.edu/resources/search-help/) |
| [EBSCOhost](https://www.ebsco.com/) | Search a library's subscribed databases through authorized access. Public product pages are useful for identifying coverage. The EBSCO Discovery Service API is a customer service and its availability does not establish access to any particular database. [EDS API information](https://about.ebsco.com/sites/default/files/acquiadam-assets/EBSCO-Discovery-Service-Tech-Sheet.pdf) |
| [ProQuest](https://www.proquest.com/) | Dissertations and specialist collections where relevant. Public records may surface through the web or institutional repositories. Collection search and full text depend on subscription and holdings. [TDM Studio](https://about.proquest.com/globalassets/proquest/files/toolkits/tdm-quick-guide-2022-oct.pdf) is a separate institutional offering. |
| [ScienceDirect](https://www.sciencedirect.com/) | Targeted verification or adjacent disciplines. Public record pages and some open text. The ScienceDirect API requires an activated key and verified entitlement. [Elsevier developer portal](https://dev.elsevier.com/sd_apis.html) |
| [SpringerLink](https://link.springer.com/) | Books, chapters and articles. Public discovery and records, with mixed access to full text. Springer Nature documents metadata and open-access content APIs with registered keys and plan limits. [API authentication](https://dev.springernature.com/docs/quick-start/authentication/) and [Open Access API](https://dev.springernature.com/docs/api-endpoints/open-access/) |
| [Wiley Online Library](https://onlinelibrary.wiley.com/) | Verify relevant publisher records. Full text varies by item and entitlement. Wiley points researchers to Crossref for citation metadata and documents separate text-mining access. [Text and data mining](https://onlinelibrary.wiley.com/library-info/resources/text-and-datamining) |
| [Taylor & Francis Online](https://www.tandfonline.com/) | Targeted humanities and area-studies journal discovery and verification. Public records and mixed full-text access. [Publisher terms](https://www.tandfonline.com/page/terms-and-conditions) |
| [Historical Abstracts](https://about.ebsco.com/products/research-databases/historical-abstracts) | Specialist international history indexing. Check the product's geographical and chronological scope against the topic. Database search usually needs institutional EBSCO access, and the indexing record does not establish full-text entitlement. |

## International indexes, repositories and research-sharing services

| Source | When to use it and what access to expect |
| --- | --- |
| [Google Scholar](https://scholar.google.com/) | Broad discovery, cited-by links and alternate versions when the interface is accessible. Public search can block automated clients. Follow provider limits and use other indexes when blocked. Verify at the publication or repository record. [Search help](https://scholar.google.com/intl/us/scholar/help.html) |
| [Semantic Scholar](https://www.semanticscholar.org/) | Metadata and citation discovery, with open-copy links where supplied. Public web search and a documented Graph API with shared anonymous limits and some key-restricted routes. Do not depend on a publication-language filter. [API documentation](https://api.semanticscholar.org/api-docs/) |
| [OpenAlex](https://openalex.org/) | Broad work discovery, citation links and open-access locations. The documented API offers limited keyless use, a larger budget with a free account key and paid higher-volume options. Works language metadata and filtering can help shortlist. Verify language and any open copy against the work or its host. [API reference](https://help.openalex.org/api/) and [authentication](https://help.openalex.org/api/authentication/) |
| [CORE](https://core.ac.uk/) | Discover repository records and available text. Coverage and full-text availability depend on deposits. CORE documents an API with a rate-limited basic tier, registration options and licensing terms. Check current limits and licensing before use. [FAQ](https://core.ac.uk/faq) and [terms](https://core.ac.uk/terms) |
| [DOAJ](https://doaj.org/) | Discover open-access journals and indexed articles. Search public metadata and follow the publisher link for text. DOAJ documents programmatic metadata access. Publisher deposit credentials are a separate matter. [Metadata help](https://doaj.org/docs/faq/) and [terms](https://doaj.org/terms/) |
| [BASE](https://www.base-search.net/) | Repository and catalog discovery. Follow records to the host for access. The documented OAI interface is for harvesting metadata, with its own conditions. Use public search when available. [OAI documentation](https://oai.base-search.net/) |
| [Academia.edu](https://www.academia.edu/) | Secondary lead for an author-uploaded copy. Login may be needed. Verify publication status at a journal, publisher, or institutional record. [Paper access help](https://support.academia.edu/hc/en-us/articles/360043939793-Are-papers-on-Academia-free) |
| [ResearchGate](https://www.researchgate.net/) | Secondary lead or author-uploaded version. Availability varies and requests can require an account. Verify the version and publication status elsewhere. [Access help](https://help.researchgate.net/research-and-publications/discovering-and-requesting-research) |
| [SSRN](https://www.ssrn.com/) | Working papers and preprints where relevant. Public abstracts and some downloadable text. Confirm published versions separately and label the version cited. [SSRN help](https://papers.ssrn.com/sol3/ssrnhelp.html) |
| [Crossref](https://www.crossref.org/) | Confirm DOI deposits and citation metadata. Public REST access needs no account. A contact email can identify polite traffic, and Metadata Plus has a key and separate limits. Deposits may omit language, abstracts or fields. Full-text links point to the content host. [Authentication and limits](https://www.crossref.org/documentation/retrieve-metadata/rest-api/access-and-authentication/) and [full-text links](https://www.crossref.org/documentation/retrieve-metadata/rest-api/text-and-data-mining-for-researchers/) |

## National and regional starting points

| Source | When to use it |
| --- | --- |
| [Lituanistika](https://www.lituanistika.lt/) | Lithuanian studies and related humanities or social science research, including relevant work in other languages. |
| [BazHum](https://bazhum.muzhp.pl/) | Polish humanities and social-science journals. Check both bibliographic data and any available digitized issues. |
| [Biblioteka Nauki](https://bibliotekanauki.pl/) | Polish scholarly journals and books, including open copies where available. |
| [Regesta Imperii OPAC](https://opac.regesta-imperii.de/) | Useful for medieval European history and relevant historical bibliography. Select it when coverage fits the period and subject. |

Add relevant national library catalogs, university repositories, specialist bibliographies and national scholarly indexes for the question. A country's index may contain scholarship in several languages.

## Capability checks for future integrations

Before adding or invoking a direct integration, check the provider's official documentation for public search, API scope, credentials, metadata, full-text rights, language filters, rate limits and terms. Test the exact path on the target host with authorized access. Record untested capabilities as unverified. Respect provider terms, robots directives, rate limits, subscriptions and authentication boundaries. When a site blocks access, use a permitted alternative and report the route actually used.
