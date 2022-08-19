# ILDG standards
## File Format

* ILDG Binary File Format (Rev. 1.1) [[Media:Ildg-file-format.pdf]]
** All binary files uploaded to the ILDG storage elements have to comply to the rules defined in the ILDG Binary File Format standard.

== Metadata ==

* QCDml Ensemble Schema
** XML Schema for specifying ensemble metadata
*** Ensemble Schema v1.4.6 [[Media:QCDmlEnsemble1.4.6.xsd]]
*** Ensemble Schema v1.4.5 [[Media:QCDmlEnsemble1.4.5.xsd]]
*** Ensemble Schema v1.4.4 [[Media:QCDmlEnsemble1.4.4.xsd]]
*** Ensemble Schema v1.4.3 [[Media:QCDmlEnsemble1.4.3.xsd]]
*** Ensemble Schema v1.4.2 [[Media:QCDmlEnsemble1.4.2.xsd]]
*** Ensemble Schema v1.4.1 [[Media:QCDmlEnsemble1.4.1.xsd]]
*** Ensemble Schema v1.4.0 [[Media:QCDmlEnsemble1.4.0.xsd]]
*** Ensemble Schema v1.3.0 [[Media:QCDmlEnsemble1.3.0.xsd]]

* Document QCDml Configuration Schema
** XML schema for specifying configuration metadata
*** Configuration Schema v1.3.1 [[Media:QCDmlConfig1.3.1.xs]]
*** Configuration Schema v1.3.0 [[Media:QCDmlConfig1.3.0.xs]]

== Middleware ==

* Introduction to MW architecture
** a brief introduction 
* [The Schema for the ILDG Service Description File](http://www.lqcd.org/ildg/Services.xsd)
** Schema for the XML file specifying the locations of ILDG services 

## Metadata Catalog
Web service for querying metadata 

* ILDG MDC WSDL [[Media:ILDG-MDC.wsdl]]
** ILDG MDC WSDL file 
* File ILDG MDC Testing Spec [[Media:ILDG-MDC-WS-1.0-TESTING.pdf]]
** Guidelines of MDC testing
* Java Signatures
** Java methods generated from the WSDL
 public ildg.mdc.ws.QueryResults doEnsembleURIQuery(java.lang.String queryFormat, java.lang.String queryString, int startIndex, int maxResults) throws java.rmi.RemoteException;
 public ildg.mdc.ws.QueryResults doConfigurationLFNQuery(java.lang.String queryFormat, java.lang.String queryString, int startIndex, int maxResults) throws java.rmi.RemoteException;
 public ildg.mdc.ws.MetadataResult getEnsembleMetadata(java.lang.String ensembleURI) throws java.rmi.RemoteException;
 public ildg.mdc.ws.MetadataResult getConfigurationMetadata(java.lang.String configurationLFN) throws java.rmi.RemoteException;
 public ildg.mdc.ws.MDCinfo getMDCinfo() throws java.rmi.RemoteException;

## File Catalog
Web service for mapping logical file names to URLs. The service previously known as Replica Catalog. 

* There are currently no items. 

## File Access
Access of data files using SRM, dCache or gridftp 

* There are currently no items.
