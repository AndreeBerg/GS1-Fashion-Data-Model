# GS1-Fashion-Data-Model
Further development of the fashion data model.
This repository contains all necessary information for the fashion industry to implement data exchange in the GS1 Fashion data model.
# Motivation
The GS1 aims to facilitate data exchange for participants in the fashion industry. Faster production cycles, a larger number of data exchange partners and the increasing importance of product data in times of e-commerce require a smooth data exchange. The agreement of a standard ensures that a uniform "language" is spoken within the fashion industry. The focus has been placed on simple use and implementation, as well as on the needs of internationalization and the associated multilingualism of data.
# Content
- Fashion data model_AT_DE_CH_V1_Pilot.xlsx
- JSON scheme for validating JSON messages
- JSON Example data set
- Update fashion data model in pilot project

This syntax-neutral Excel Pilot data model was created in cooperation with the companies Ahlers Group, Hagemeyer, Zalando, KATAG, Falke and Fashion Cloud.
- In Sope 1 of the implementation, the focus is on the attributes that can be delivered by the data sender today.
- In Sope 2-n, an extension is planned to include attributes that are required for online.
- The goal is to give the data sender an overview of future requirements, which he can then implement in his internal processes with the appropriate time buffer.

# The Excel pilot data model is structured as follows:

- It serves as basic information with all attributes defined by the industry up to now and in the future
- filtering in column I on Scope 1 with 59 attributes for the start of electronic data exchange

Since the fashion industry wants to be technologically independent, we have tried to depict several communication standards, which will now be tested live with active pilots. In detail these are:

- Definition of the attributes that can be transmitted to PRICAT (column N-P)
- A description of the structure of the JSON blueprint as a schema and documentation on how to create an api interface description
- Documentation on how to create an XML API interface description for these 59 attributes

# XML Schema Definition

The JSON Schema helps to create valid JSON documents in the Fashion Data Model. The generation of an XML schema (=XSD, XML Schema Definition) is possible with little effort using online tools like https://www.freeformatter.com/json-to-xml-converter.html. To do this, one would first convert the JSON sample file online into XML. Then you can generate an XSD from the XML, which must then be filled with the valid value ranges from the JSON schema.

