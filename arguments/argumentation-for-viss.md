# Argumentation for VISS

The development of the open specification Vehicle Information Service Specification (VISS) was initiated at the World Wide Web Consortium (W3C) in 2013. VISS version 1 was published in 2018. Just before the release of VISS version 2.0 in 2024 the hosting of the specification development was transferred from W3C to the Connected Vehicle Systems Alliance (COVESA). VISS version 3.0 was released in 2025.

This latest version 3.0 is not only supported by COVESA but it has also been adopted by AUTOSAR in their R24-11 publication., and ACEA says in a MoU that they want to work with COVESA on further development of VISS.

Important features of the specification:

* Explicitly supported transport protocols: HTTP / Websocket / gRPC / MQTT
* Actions on data: Get / Set / Subscribe / Unsubscribe
* Data model: COVESA Vehicle Signal Specification (VSS)
* Subscribe variants: Time period / Change / Range / Curve logging
* File transfer: Download / Upload
* Access control: JSON web-token, Role Based, Auth 2.0 inspired (authentication not specified)
* Prepared for integration with external user consent framework


VISS is a comprehensive  open vehicle interface specification that has been developed and refined over a long period of time by multiple automotive OEMs and others from the automotive domain. It is hosted by COVESA where it is developed by a working group that is open for anyone to participate in.


Links:

[VISSv1](https://www.w3.org/TR/vehicle-information-service/)

[VISSv2.0](https://github.com/COVESA/vehicle-information-service-specification/releases/tag/v2.0)

[VISSv3.0](https://github.com/COVESA/vehicle-information-service-specification/releases/tag/v3.0)

[VSS](https://github.com/COVESA/vehicle_signal_specification)

[AUTOSAR R24-11](https://www.autosar.org/search?tx_solr%5Bfilter%5D%5B1%5D=platform%3AAP&tx_solr%5Bfilter%5D%5B2%5D=category%3AR24-11&tx_solr%5Bq%5D=)

[COVESA-ACEA MoU](https://www.acea.auto/press-release/auto-makers-and-covesa-sign-memorandum-of-understanding-to-advance-interoperability-in-commercial-vehicles/)
