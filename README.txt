CSPP_LNA extends the CSPP_Core package of the CS++-Project. 

It contains CS++LNAMessage.lvclass, a derived class of Message.lvclass

Refer to https://github.com/HB-GSI/CSPP for CS++ project overview, details and documentation.

LabVIEW 2014 is the currently used development environment.

Related documents and information
=================================
- README.txt
- Release_Notes.txt
- EUPL v.1.1 - Lizenz.pdf
- Contact: H.Brand@gsi.de or D.Neidherr@gsi.de
- Download, bug reports... : http://github.com/HB-GSI/CSPP_LNA
- Documentation:
  - Refer to package folder
  - Project-Wiki: https://github.com/HB-GSI/CSPP/wiki
  - NI Actor Framework: https://decibel.ni.com/content/groups/actor-framework-2011?view=overview

GIT Submodules
==============
This package can be used as submodule
- Packages\CSPP_LNA:
  - CS++LNA.lvlib

External Dependencies
---------------------

Optional submodules
-------------------
- CSPP_Examples: TestLNA

Getting started:
=================================
- Add CS++LNA.lvlib into your own LabVIEW project.
- Add CS++LNAMessage.lvclass into your desired case of the CS++UserContents.vi
- A dynamic dispatch "Parameter to Attribute.vi" with variant input needs to be added to Message.lvclass in order to work properly. Refer to CS++LNAMessage.lvclass:Do.vi for details.
- Message classes to be dispatched using CS++LNAMessage.lvclass need to override "Parameter to Attribute.vi"and parse the paramater variant attributes to its own object attibutes.

Author: H.Brand@gsi.de, D.Neidherr@gsi.de

Copyright 2013  GSI Helmholtzzentrum für Schwerionenforschung GmbH

Planckstr.1, 64291 Darmstadt, Germany

Lizenziert unter der EUPL, Version 1.1 oder - sobald diese von der Europäischen Kommission genehmigt wurden - Folgeversionen der EUPL ("Lizenz"); Sie dürfen dieses Werk ausschließlich gemäß dieser Lizenz nutzen.

Eine Kopie der Lizenz finden Sie hier: http://www.osor.eu/eupl

Sofern nicht durch anwendbare Rechtsvorschriften gefordert oder in schriftlicher Form vereinbart, wird die unter der Lizenz verbreitete Software "so wie sie ist", OHNE JEGLICHE GEWÄHRLEISTUNG ODER BEDINGUNGEN - ausdrücklich oder stillschweigend - verbreitet.

Die sprachspezifischen Genehmigungen und Beschränkungen unter der Lizenz sind dem Lizenztext zu entnehmen.