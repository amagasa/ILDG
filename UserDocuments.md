== Joininig the ILDG VO ==

A description of the process for joining the ILDG Virtual Organisation. 

 Summary of process for joining the ILDG VO
 ==========================================
 
 To access ILDG resources and data, a person needs to be a member of the
 ILDG Virtual Organisation (VO). The VO is hosted on a VOMS system [1].
 
 The process of joining the VO can be completed via the VOMS Admin web
 interface:
 
   https://grid-voms.desy.de:8443/voms/ildg/
 
 -- provided that the user has a grid certificate from a recognised
 Certification Authority (CA) [2].
 
 The user should fill in the application form and confirm their
 acceptance of the Acceptable Use Policy (AUP) for the ILDG VO. Once this
 is done, an (email) alert is sent to the VO administrators. The user
 should then be approved by an appropriate representative for their
 regional grid. Once approved, an applicant becomes a 'member' of the VO.
 
 Notes and caveats:
 
 - The ILDG VO Policy determines that it is the responsibility of a
   regional-grid administrator (from the applicant's own regional grid)
   to either approve the application and assign the applicant to the VOMS
   sub-group that corresponds to their regional grid, or to reject the
   application.
 
 - During the application process, the user should access the VOMS Admin
   page from a web browser in which the certificate that they intend to
   use for authentication has previously been imported. They should
   identify themselves using this certificate.
 
   The Distinguished Name (DN) of the certificate with which the user has
   authenticated themselves is displayed at the top right-hand side of
   each web page in VOMS.
 
 - Once an application is approved, the status change is quickly
   propagated to the VOMS service. However, it may take more time for
   regional-grid services to support access for new members since they
   pull the VO membership lists at non-specified time intervals (ranging
   from once per hour to once per day).
 
 - A user may need to register again with the VO if either their DN or
   the DN of the CA that issued their certificate changes, though it is
   also possible for a VO administrator to make these changes.
 
 - In case of problems, one may submit an email to
   <ildg-vo-support@desy.de>.
 
 References
 ----------
 
 [1] VOMS -- https://twiki.cern.ch/twiki/bin/view/EMI/EmiVOMSSRC
 
 [2] Recognised CAs -- http://www.igtf.net/
