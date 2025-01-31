## Conclusion and Future Work
{:#conclusion}

The most important achievement of this work,
is the strong impact it had on the [decision taken by ERA](https://www.era.europa.eu/sites/default/files/agency/docs/decision/decision_n250_annex1_linked_data_en.pdf)[^era-decision] to
make Semantic Web technologies
the default setting for any future development of data,
registers and specifications under the agency's remit.
Considering ERA's position as a European authority
this decision could potentially influence
the different stakeholders in the railway domain to take similar paths.

The results obtained from this work,
demonstrated with a practical approach,
how Semantic Web technologies enable higher data interoperability.
Data integration is achieved at the _data level_ (data-centric)
instead of being locked into application-specific business logic (application-centric),
opening the door for new and innovative use cases.
We were able to create a semantic interoperability layer
over the different considered data sources,
which requires significantly less effort to be created and managed,
compared to developing ad hoc applications
and 1-to-1 interfaces between different information systems.
Furthermore, this work also demonstrated
that Semantic Web technologies can be used to create
functional Web applications based on modern
and developer-friendly frameworks such as React
with little additional effort from a development perspective
and in a reasonable time frame.

The choice of architecture design made for this prototype
leverages HTTP caching mechanisms to achieve higher scalability
while providing full querying flexibility to client applications.
This is demonstrated by the ability of the RCC client application
to perform route planning calculations over the ERA KG,
which are not supported by standard RDF triple stores.
Yet, this approach establishes a trade-off
between scalability and flexibility vs. performance.
Further optimizations are required to achieve production-level performance
without losing the benefits of the proposed solution architecture.

For future work, we aim to explore how more granular descriptions
of the railway, topology can be integrated to increase the reliability of the ERA KG.
From an architectural perspective,
stream-processing and KG virtualization approaches may be studied
to support use cases with higher requirements on up-to-date data.
