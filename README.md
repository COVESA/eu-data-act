![Status - Incubating](https://img.shields.io/static/v1?label=Status&message=Incubating&color=FEFF3A&style=for-the-badge)

# EU Data Act Project

We propose to cooperate within COVESA on proposing open standards for
interoperability of data processing services.

COVESA is well-positioned to host a collaborative project, in three
phases, during which:

* Phase 1 (Understanding): A combined understanding of the legislative
  requirements can be reached, perhaps in active collaboration with
  the activities of ACEA, the German VDA and other relevant bodies.

* Phase 2 (Evaluate): An objective evaluation of Vehicle Signal
  Specification (VSS) against those requirements.

* Phase 3 (Design and Deliver Proposal): To the extent VSS meets the
  requirements, a set of proposals based on OEM-consensus delivered to
  the automotive industry broadly and specifically to the Commission.

A successful outcome of this activity will be a clear understanding of
how VSS meets \- or falls short of meeting \- legislative requirements
of the Act. Should VSS meet the requirement, then a positive outcome
would be active OEM adoption as part of the short- or long-term
compliance to the requirements. A likely side benefit may be that VSS
evolves to be a better solution for OEMs complying to the Act.

The proposed goals of the collaboration project are:

1. Gain a consistent, industry-wide understanding of Data Act
requirements, in collaboration with ACEA, German VDA and others.

2. Evaluate VSS against that consistent understanding

3. Recommend, develop and deliver OSS specifications from which OEMs
can evaluate their respective compliance strategy such as:

   1. Commit to data schema format (VSS or similar) \- Payload
   structure \- Use VSS YAML format.

   2. Commit to secure data transmission mechanism from cloud to user
   / third party \- VISS or similar

   3. Commit to common baseline vehicle data specification/description
      (VSS or similar) to be adopted and extended by OEMs as they see
      fit. (content of VSS file).  E.g. vehicle speed is described and
      transmitted the same way for all OEMs.

   4. Determine consent management process, taking into account OEM,
   3rd party, user and government perspectives

   5. Explore interaction of data transfer mechanisms with Consent
   Management process.


## Background (EU Data Act)

During 2025 and 2026 EU Data Act (EUDA) Legislation will start to come
into effect, and the automotive industry needs to prepare. OEMs and
suppliers, selling vehicles in Europe, including several COVESA
members, need to understand the compliance requirements and determine
their own course of action in a relatively short period of time.

In the regulation Article 30 and 35, discussion on interoperability
and EU centralized repo for standards which refers to having standards
for automotive as well. The motivation is to have a common standard
for automotive and VSS could be the proposed standard for automotive.

Regulation link : [Regulation (EU) 2023/2854 of the European
Parliament and of the Council of 13 December 2023 on harmonised rules
on fair access to and use of data and amending Regulation (EU)
2017/2394 and Directive (EU) 2020/1828 (Data
Act)](https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=OJ:L_202302854&qid=1711373839244)

Reference to Article 30 (3)

Each OEM will have to analyze the implications of the EUDA and
implement solutions accordingly.

However, the European Commission’s Directorate-General for
Communications Networks, Content and Technology (DG CNECT) has
commissioned a study on “interoperability of data processing
services”. The ambition is to set up a centralized repository of
standards to be used for interoperability according to the article 30
above. There is a high likelihood that this will drive unified
standards for e.g. exchanging vehicle data with Insurance companies.


## Disclaimer

Specifications created by the project does not guarantee that it will
be implemented by an OEM.

Vehicle data capabilities are dependent on the configuration of a
vehicle. We are not defining any vehicle requirement.


## Examples

### ACEA Level A1

The mapping of the ACEA proposal for a predefined data list, Level A1,
to VSS builds upon the work on [Issue
#180](https://github.com/COVESA/vehicle_signal_specification/issues/180)
in the COVESA `vehicle_signal_specification` GitHub repository.
