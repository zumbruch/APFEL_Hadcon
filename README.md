##APFEL Hadcon - Controlling the APFEL via HadCon2

This project comprises all submodules which are necessary to control the APFEL ASIC connected to an HadCon2 board,
which itself is connected to a linux PC (Raspberry PI) running an EPICS IOC.

These are:
  * The HadCon2 (Atmel AVR) Firmware sources 
     * &rArr; _Firmware/HadCon2_
  * The EPICS IOC sources for StreamDev2/ASCII based access to the HadCon2
     * &rArr; _EPICS/IOC/_
     * incl. the startup code for a procServ/crontab based automatic startup
         * &rArr; ... 
  * The CSS GUI sources
     * &rArr; _EPICS/CSS/_  
  
Documentations:
 * [HadCon2] (https://wiki.gsi.de/Epics/HadCon2)
 * Firmware: [HadCon2 Protocol Apfel command](https://wiki.gsi.de/Epics/HadConMultipurposeControlsProtocolCmndApfel)
 * IOC - nya
 * CSS - nya

Author: P.Zumbruch_at_gsi.de

Copyright May, 2015  GSI Helmholtzzentrum für Schwerionenforschung GmbH

Planckstr.1, 64291 Darmstadt, Germany

Lizenziert unter der EUPL, Version 1.1 oder - sobald diese von der Europäischen Kommission genehmigt wurden - Folgeversionen der EUPL ("Lizenz"); Sie dürfen dieses Werk ausschließlich gemäß dieser Lizenz nutzen.

Eine Kopie der Lizenz finden Sie hier: http://www.osor.eu/eupl

Sofern nicht durch anwendbare Rechtsvorschriften gefordert oder in schriftlicher Form vereinbart, wird die unter der Lizenz verbreitete Software "so wie sie ist", OHNE JEGLICHE GEWÄHRLEISTUNG ODER BEDINGUNGEN - ausdrücklich oder stillschweigend - verbreitet.

Die sprachspezifischen Genehmigungen und Beschränkungen unter der Lizenz sind dem Lizenztext zu entnehmen.
