# SSV/WebUI-Funktionen: RMG/938

Vor der ersten Inbetriebnahme bitte unbedingt das Handbuch *Remote Maintenance Gateway RMG/938 - First Steps* durchsehen, siehe https://ssv-comm.de/forum/dokumente/RMG938_FS_A.pdf. In dem Handbuch finden Sie unter *Accessing the SSV/WebUI* eine Beschreibung wie Sie von Ihrem PC aus per Webbrowser auf das SSV/WebUI zugreifen und sich als Adminstratur in dieser Web-basierten Konfigurationsoberfläche anmelden können.  

Nach einer erfolgreichen Anmeldung wird Ihnen im Browserfenster eine horizontale Menüleiste mit den zur Verfügung stehenden Funktionen angezeigt.  

![Übersicht: Menü](https://ssv-comm.de/forum/bilder/938-menue.png)

## 1. Status 

![Menü: Status](https://ssv-comm.de/forum/bilder/938-status.png) 

Übersichtsseite mit dem aktuellen Systemstatus sowie den Adressen aller IP-Schnittstellen plus Zusatzinformationen zu DNS-Servern und dem Default-Gateway.

## 2.1 System > System identification 

![Menü: System > System identification](https://ssv-comm.de/forum/bilder/938-system_1.png) 

In dieser Webseite des SSV/WebUI sind verschiedenen Eigenschaften zur Gateway-Identifikation zusammengefasst.

**Host name:** Eingabe eines beliebigen Namens, um ein bestimmtes Gateway sicher identifizieren zu können.

**Location:** Eingabe der Standortinformationen bzw. Angaben, um den Installationsort eines bestimmten Gateways zu finden.

**Contact:** E-Mail-Adresseingabe, um den zuständigen Betreuer des Gateways erreichen zu können. 

**Serial number:** Voreingestellte Seriennummer des Gateways. Über diese Nummer lassen sich Rückfragen zur Produktionswoche, Werkseinstellungen, Auslieferung usw. mit Hilfe der Herstellerdatenbank beantworten.

**Indentify device through front LED:** Ein Druck auf die Flash-Schaltfläche bewirkt, dass eine der Frontplatten-LEDs des Gateways ca. 5 Sekunden lang blinkt. Dadurch lässt sich ein bestimmtes Gateway visuell identifizieren.

## 2.2 System > System management 

![Menü: System > System management](https://ssv-comm.de/forum/bilder/938-system_2.png) 

Über die hier zusammengefassten Funktionen lassen sich ein Systemneustart (Reboot) erzwingen und die Konfigurationseinstellungen vervielfältigen bzw. in den werksseitigen Ausgangszustand zurücksetzen.

**Reboot system:** Das Betriebssystem des Gateways wird heruntergefahren. Anschließend erfolgt ein Neustart. Die WebUI-Sitzung muss anschließend neu gestartet werden. Durch diese Aktion gehen nicht unter Umständen nicht gespeicherte Einstellungen verloren.

**Configuration download:** Die auf diesem Gateway per Web/UI eingestellte Konfiguration kann mit dieser Funktion als Datei zum PC heruntergeladen und gespeichert werden.

**Configuration upload:** Eine auf dem PC gespeicherte Datei mit Konfigurationseinstellungen wird zum Gateway hochgeladen werden, um die Einstellungen aus der Datei zu übernehmen. ***Achtung: Durch diese Aktion gehen Ihre Gateway-Einstellungen verloren. Sie werden durch die hochgeladene Datei überschrieben. Dadurch können Sie sich für weitere Zugriffe aus dem SSV/WebUI aussperren.*** 

**Configuration reset:** Ermöglicht das Rücksetzen der von Ihnen per SSV/WebUI vorgenommenen Einstellungen in den werkseitig voreingestellten Zustand. Details zur werkseitig voreingestellten IP-Adresse usw. finden Sie im *Handbuch Remote Maintenance Gateway RMG/938 - First Steps*, siehe https://ssv-comm.de/forum/dokumente/RMG938_FS_A.pdf.

## 2.3 System > Firmware update 

![Menü: System > Firmware update](https://ssv-comm.de/forum/bilder/938-system_3.png) 

**Firmware info:** In diesem Bereich werden Ihnen die aktuelle Firmware-Version sowie eine Hash-Wert für Integritätsprüfungen zum installierten Firmware-Image angezeigt. 

**Firmware update configuration:** Ihr Gateway unterstützt verschiedene Remote-Update-Möglichkeiten. Dabei werden einzelne Softwarekomponenten oder sogar eine vollständig neue Firmware von einem vertrauenswürdigen Server heruntergeladen und installiert. Software-Updates sind eine kritische Angelegenheit. Kontaktieren Sie im Zweifelsfall vor einem Update unseren Support.

## 2.4 System > App management 

![Menü: System > App management](https://ssv-comm.de/forum/bilder/938-system_4.png) 

Die Funktionen des Gateways lassen sich über spezielle Apps erweitern. Die meisten Apps stehen Ihnen kostenlos zur Verfügung. Für einige Apps ist eine kostenpflichtige Lizenz erforderlich, die Sie über Ihren Vertriebskontakt erwerben können.

**Install app:** Diese Funktion liefert Ihnen eine aktuelle Übersicht der für dieses Gateway zur Verfügung stehenden Apps plus die jeweiligen Versionsnummern. Die Übersicht entsteht durch einen Online-Zugriff auf einen externen Server. Diese Funktion erfordert daher eine Internetverbindung des Gateways. Über die Schaltfläche am rechten Rand der jeweiligen Zeile können Sie die gewünschte App installieren.

**Installed apps:** Hier werden Ihnen die jeweils installierten Apps zusammen mit den jeweiligen Versionsangaben angezeigt. Über die Informations-Schaltfläche lassen sich weitere Informationen zur betreffenden App einblenden. Darüber hinaus können Sie über die Schaltfläche mit dem Mülleimer-Symbol auch bereits installierte Apps jederzeit wieder löschen. 

## 2.5 System > Time and date 

![Menü: System > Time and date](https://ssv-comm.de/forum/bilder/938-system_5.png) 

**Local time zone configuration:** Hier wird die Zeitzone ausgewählt, in der das Gateway betrieben wird. Die Einstellung ist erforderlich, um bei einer Zeitsynchronisation mit Zeitservern im Internet die erforderliche Korrektur durchzuführen (Korrektur in Bezug auf Greenwich Mean Time, also die mittlere Sonnenzeit am Greenwicher Nullmeridian). 

**Time and date configuration:** An dieser Stelle können Sie auswählen, ob die interne Gateway-Echtzeituhr über einen externen Zeitserver in einem lokalen Netzwerk oder im Internet periodisch synchronisiert wird oder ob eine (einmalige) manuelle Zeitsynchronisation über die SSV/WebUI-Verbindung erfolgen soll. 

## 2.6 System > COM ports 

![Menü: System > COM ports](https://ssv-comm.de/forum/bilder/938-system_6.png) 

Die seriellen Schnittstellen des Gateways lassen sich für unterschiedliche Anwendungen universell nutzen. Über diese Webseite des SSV/WebUI können Sie einzelne Schnittstellen für den Betrieb als serielle Konsole (Remote console) oder als „Com port redirector“ reservieren. Durch eine solche Reservierung steht die jeweilige Schnittstelle nicht mehr für andere Anwendungen zur Verfügung.

Bitte beachten: Der COM1-Port dieses Gateways befindet sich innerhalb des Gehäuses. Es ist von außen nicht zugänglich. Diese Schnittstelle ist fix als serielle Konsole für Servicezwecke vorgesehen. Eine andere Verwendung ist nicht möglich. Für die weiteren Schnittstellen gibt es drei Optionen:

**None:** Die serielle Schnittstelle kann durch beliebige Anwendungen genutzt werden, z. B. unter Node-RED für die Modbus-basierte Kommunikation mit externen Baugruppen. 

**Remote console:** Die jeweilige serielle Schnittstelle bildet eine Konsole für die Kommunikation mit dem Linux-Betriebssystem. Beachten Sie bitte, dass für die Benutzung eine Anmeldung mit Benutzername und Passwort erforderlich ist.

**Com port redirector:** Diese Funktion bildet einen Protokollkonverter zwischen den IP-basierten Transportprotokollen UDP oder TCP, die z. B. für die LAN-Schnittstellen zur Verfügung stehen, und der jeweils zugewiesenen seriellen Schnittstelle. Die UPD bzw. TCP-Seite kann wahlweise im Client- oder Servermodus betrieben werden. 

## 2.7 System > Watchdog 

![Menü: System > Watchdog](https://ssv-comm.de/forum/bilder/938-system_7.png)

Ihr Gateway verfügt über verschiedene Wachdog-Zeitgeber bzw. Watchdog-Zähler, die einen möglichst störungsfreien 24/7-Betrieb gewährleisten sollen. Für diese Watchdogs stellen individuelle Konfigurationseinstellmöglichkeiten zur Verfügung.

**Enable watchdog service:** Watchdog-Dienste des Gateways ein- oder ausschalten.

**Enable default watchdog:** Die hier aufgeführten einzelnen Watchdogs mit den werksseitigen Default-Einstellungen aktivieren.

**Reboot interval:** Einstellen einer Zeitspanne, nach der automatisch ein Reboot des Gateways ausgelöst wird. Durch den Gateway-Reboot werden alle Systemprozesse in einen (definierten) Ausgangszustand gesetzt.  

Ein typischer Anwendungsfall für dieses Gateway ist der Betrieb als VPN-Client in einer Fernwartungsanwendung. Dafür ist es je nach Konfiguration wichtig, dass eine dauerhafte VPN-Verbindung zu einem externen VPN-Server existiert. Wird diese VPN-Verbindung durch irgendwelche Störungen unterbrochen, muss das Gateway automatisch versuchen, den Server erneut zu erreichen. Mit den folgenden beiden Einstellmöglichkeiten lässt sich ein Gateway-Reboot erzeugen, wenn innerhalb einer bestimmten Zeit keine VPN-Serververbindung zu Stande gekommen ist oder eine bestimmte Zeit lang keine VPN-Verbindung mehr existiert.

**VPN1: Start delay:** Überwachen, ob innerhalb einer bestimmten Zeit eine VPN-Verbindung zu Stande kommt. Das Gateway kann sich nach jedem Bootvorgang automatisch einen VPN-Server kontaktieren, um sich als Client in ein VPN zu integrieren. Klappt diese Integration nicht innerhalb der hier festgelegten Zeit, wird ein Gateway-Reboot erzeugt.

**VPN1: Offline delay:** Überwachen, wie lange bereits keine VPN-Verbindung zu einem externen Server existiert. Wurde eine VPN-Verbindung zum Server unterbrochen und ist keine neue Verbindung zu Stande gekommen, wird nach Ablauf der hier voreingestellt Zeit ein Reboot erzeugt.

Ein Gateway unterhält in vielen Anwendungsfällen gleichzeitig lokale Verbindungen zu anderen Systemen sowie verschiedene externe Verbindungen ins Internet  (s. g. WAN-Verbindungen = Wide Area Network-Verbindungen), z. B. zu einem Zeitserver und weiteren speziellen Cloud- und IoT-Serviceplattformen. WAN-Verbindungen sind deutlich störungsanfälliger als eine lokale Verbindung. Über die folgenden drei Einstellmöglichkeiten lässt sich eine Datenmengen-basierte WAN-Zustandsüberwachung konfigurieren, um im Störungsfall einen automatischen Restart der WAN-Schnittstellen-Hardware auszulösen (beispielsweise ein Reset für das interne Mobilfunkmodem).

**WAN: Traffic threshold:** Anzahl der Bytes pro Minute, die mindestens aus dem WAN in Richtung Gateway übertragen werden müssen, wenn eine funktionierende WAN-Verbindung existiert. Dieser Schwellwert legt fest, ob die WAN-Verbindung als OK oder kritisch (unbestimmt) eingestuft wird. (Achtung: Diese Funktion ist nur für Gateways mit einem internen Mobilfunkmodem sinnvoll nutzbar)

**WAN: Start delay:** Zeitspanne, innerhalb welcher nach einem Gateway-Bootvorgang die per Schwellwert (siehe *Traffic threshold*) festgelegte Anzahl Bytes pro Minute erreicht werden muss. Ansonsten wird nach Ablauf der hier voreingestellt Zeit ein WAN-Schnittstellen-Hardware-Restart erzeugt. (Achtung: Diese Funktion ist nur für Gateways mit einem internen Mobilfunkmodem sinnvoll nutzbar)

**WAN: Idle delay:** Zeitspanne, die maximal vergehen darf, ohne das die per Schwellwert (siehe *Traffic threshold*) festgelegt Anzahl Bytes pro Minute erreicht werden muss. Ansonsten wird nach Ablauf der hier voreingestellt Zeit ein WAN-Schnittstellen-Hardware-Restart erzeugt. (Achtung: Diese Funktion ist nur für Gateways mit einem internen Mobilfunkmodem sinnvoll nutzbar)

**Mobile: reset count:** Diese Funktion ist nur für Gateways mit einem internen Mobilfunkmodem vorgesehen.

**Mobile: reboot count:** Diese Funktion ist nur für Gateways mit einem internen Mobilfunkmodem vorgesehen.

## 2.8 System > Logging 

![Menü: System > Logging](https://ssv-comm.de/forum/bilder/938-system_8.png)

Das Gateway erzeugt zur Laufzeit eine Logging-Datei mit umfangreichen Einträgen. Sie dient zur Diagnose bzw. Ursachensuche bei Auffälligkeiten im Systemverhalten und anderen Ereignissen. Die Logging-Datei wird bei jedem Gateway-Bootvorgang neu erzeugt und geht beim Ausschalten der Versorgungsspannung verloren. 

**Download log file:** Mit dieser Funktion können Sie die Logging-Datei zu Ihrem PC herunterladen und dort speichern.

**Download service startup graph:** Über diese Eigenschaft können Sie eine Grafik mit einer Übersicht zum Start einzelner Systemdienste zum PC herunterladen und dort speichern. 

## 3.1 Network > WAN 

![Menü: Network > WAN](https://ssv-comm.de/forum/bilder/938-network_1.png)

Ein Gateway unterhält in vielen Anwendungsfällen gleichzeitig lokale Verbindungen zu anderen Systemen sowie verschiedene externe Verbindungen ins Internet (s. g. WAN-Verbindungen = Wide Area Network-Verbindungen), z. B. zu einem Zeitserver und weiteren speziellen Cloud- und IoT-Serviceplattformen. WAN-Verbindungen sind deutlich störungsanfälliger als lokale Verbindungen. Über die folgende Einstellmöglichkeit lässt sich eine Ping-basierte WAN-Zustandsüberwachung (Ping-Watchdog) konfigurieren, um im Störungsfall eine andere physikalische Gateway-Schnittstelle als WAN-Schnittstelle auszuwählen (*WAN fallback interface*, beispielsweise LAN2 statt LAN1).

**WAN configuration:** Auswahl einer Gateway-Schnittstelle für die WAN-Verbindung (es können nur IP-fähige Schnittstellen ausgewählt werden, z. B. LAN1).

**WAN watchdog:** Hier lässt sich der Ping-Watchdog für die WAN-Schnittstelle aktivieren. Zum Aktivieren muss eine Ping-Test-Intervallzeit ausgewählt werden (z. B. jeweils ein Ping-Test alle 15 Minuten). Des Weiteren ist der DNS-Name oder die IP-Adresse des Systems auszuwählen, dass per Ping-Test über die WAN-Schnittstelle erreicht werden soll. Zusätzlich lässt sich die auszuführende Aktion für den Fehlerfall des Ping-Tests festlegen (siehe *WAN fallback interface*). 

## 3.2 Network > LAN1 

![Menü: Network > LAN1](https://ssv-comm.de/forum/bilder/938-network_2.png)

**Interface configuration for LAN1:** Ein- oder ausschalten der LAN1-Schnittstelle.

**IPv4 address configuration:** In dieser Gruppe sind die IPv4- Adresseinstellmöglichkeiten für die LAN1-Schnittstelle zusammengefasst. Sie können zwischen einer automatischen IP-Adressvergabe per DHCP oder der manuellen Adresseingabe wählen. Beachten Sie bitte, dass der LAN1-Schnittstelle mehr als eine IP-Adresse zugewiesen werden kann. 

**IPv6 address configuration:** Hier sind IPv6-Adresseinstellmöglichkeiten für die LAN1-Schnittstelle zusammengefasst. Analog zur IPv4-Adressvergabe ist eine automatische Adresszuweisung per DHCP oder die manuelle Adresseingabe von IPv6-Adressen möglich.

**Expert configurations:** Unter diesem Oberbegriff stehen verschieden „Experten-Einstellungen“ zur Verfügung. Veränderungen sollten nur durch entsprechend geschultes Fachpersonal vorgenommen werden. Einen Sonderfall bildet *Enable UPnP discovery* (UPnP = Universal Plug and Play). Ist diese Funktion eingeschaltet, können Sie mit einem UPnP-fähigen Gerät das Gateway in einem lokalen Netzwerk suchen, ohne die IP-Adresse der LAN1-Schnittstelle zu kennen. 

## 3.3 Network > LAN2 

![Menü: Network > LAN2](https://ssv-comm.de/forum/bilder/938-network_3.png)

**Interface configuration for LAN2:** Ein- oder ausschalten der LAN2-Schnittstelle.

**IPv4 address configuration:** In dieser Gruppe sind die IPv4-Adresseinstellmöglichkeiten für die LAN2-Schnittstelle zusammengefasst. Sie können zwischen einer automatischen IP-Adressvergabe per DHCP oder der manuellen Adresseingabe wählen. Beachten Sie bitte, dass der LAN2-Schnittstelle mehr als eine IP-Adresse zugewiesen werden kann.  

**IPv6 address configuration:** Hier sind IPv6-Adresseinstellmöglichkeiten für die LAN2-Schnittstelle zusammengefasst. Analog zur IPv4-Adressvergabe ist eine automatische Adresszuweisung per DHCP oder die manuelle Adresseingabe von IPv6-Adressen möglich.

**Expert configurations:** Unter diesem Oberbegriff stehen verschieden „Experten-Einstellungen“ zur Verfügung. Veränderungen sollten nur durch entsprechend geschultes Fachpersonal vorgenommen werden. 

## 3.4 Network > Bluetooth 

![Menü: Network > Bluetooth](https://ssv-comm.de/forum/bilder/938-network_4.png)

**General configuration:** Die Bluetooth Low Energy (BLE) Schnittstelle des Gateways lässt sich ein- und ausschalten.

## 3.5 Network > Firewall and NAT 

![Menü: Network > Firewall and NAT](https://ssv-comm.de/forum/bilder/938-network_5.png)

Ihr Gateway besitzt ein komplexes Firewall-System, mit dem sich der Datenverkehr aller vorhanden IP-Schnittstellen überwachen und filtern lässt. Die Einstellmöglichkeiten sind sehr umfangreich. Wen Sie die Firewall nutzen wollen, ist auf jeden Fall ein entsprechend geschulter Experte für die Einstellungen erforderlich. Alternativ können Sie sich auch jederzeit an unseren Support wenden.

Beachten Sie bitte, dass die Gateway-Firewall sowohl IPv4 als auch PPv6 unterstützt. Für beide IP-Protokollvarianten sind aber in jedem Fall jeweils eigene Regel erforderlich.

**Firewall configuration:** In diesem Bereich können Sie sich die aktuellen Firewall-Regeln anzeigen lassen und eine Log-Datei für Firewall-Diagnoseaufgaben ein- bzw. ausschalten und ansehen. 

**Firewall and NAT rules preconfigured sets:** Das Gateway besitzt einige vordefinierte Firewall-Regeln, z. B. für Anwendungen in einem Fernzugriffs-VPN. Diese Voreinstellungen lassen sich hier aktivieren bzw. an eigene Anforderungen anpassen. Des Weiteren ist unter diesen Einstellmöglichkeiten auch das Hochladen einer Datei mit vollständigen Firewall- und NAT-Regeln möglich vom PC zum Gateway (Upload eines *Firewall and NAT rules script*).  

**Formwarding with IP-Masquerading and NAT:** Unter diesem Eintrag lässt sich das NAT-basierte Routing zwischen dem Gateway und dem WAN (Wide Area Network) ein- und ausschalten. 

## 4.1 Services > General 

![Menü: Services > General](https://ssv-comm.de/forum/bilder/938-services_1.png)

Ihr Gateway besitzt aus Kompatibilitätsgründen mit älteren SSV-Produkten sowohl einen Telnet- als auch FTP-Server. Beide Protokolle gelten inzwischen als unsicher, weil sie auf einer unverschlüsselten Datenübertragung basieren. Insofern sollten diese Protokolle für den Praxiseinsatz des Gateways ausgeschaltet werden.

**General service configuration:** Hier können Sie den Zugriff per Telnet oder FTP auf das Gateway ein- oder ausschalten. Des Weiteren lässt sich der *Shellinabox*-Service aktivieren bzw. deaktivieren. *Shellinabox* (Shell-in-a-box) ist eine per Webbrowser aufrufbare Webseite, in der Sie über eine Linux-Konsole mit dem Gateway kommunizieren können.    

## 4.2 Services > OpenVPN 

![Menü: Services > OpenVPN](https://ssv-comm.de/forum/bilder/938-services_2a.png)
![Menü: Services > OpenVPN](https://ssv-comm.de/forum/bilder/938-services_2b.png)

Ein typisches Anwendungsbeispiel für industrielle Gateways ist der Einsatz in Virtual Private Networks (VPNs), um Fernwartungsanwendungen zu realisieren. Das Gateway bildet dabei einen VPN-Client-Endpunkt und ermöglicht einem Servicetechniker den sicheren Fernzugriff auf die hinter dem Gateway liegenden Baugruppen (z. B. Steuerungen in einem lokalen OT-LAN). In einer solchen Anwendung verbinden sich alle VPN-Clients mit einem zentralen VPN-Server. Ihr Gateway kann gleichzeitig die Verbindungen zu maximal drei externen VPN-Servern aufrechthalten halten (siehe Reiter *Client 1*, *Client 2* und *Client 3*). Jede Verbindung lässt sich mit unterschiedlichen Zertifikaten einzeln konfigurieren. Darüber hinaus ist das Gateway auch als VPN-Server einsetzbar (siehe Reiter *Server*).

**OpenVPN client configuration:** Für jede Client-Verbindung zu einem externen OpenVPN-Server lassen sich hier neben der OpenVPN-Server-IP-Adresse bzw. dem OpenVPN-Server-DNS-Namen unterschiedliche Protokollparameter einstellen. Diese Konfigurationen müssen durch einen entsprechend geschulten Experten erfolgen. Alternativ können Sie sich auch an unseren Support wenden. 

**OpenVPN certificates and keys:** In diesem Bereich erfolgt das Zertifikats- und Schlüsselmanagement für eine VPN-Client-Verbindung, um sich mit dem jeweiligen OpenVPN-Server verbinden zu können.

## 4.3 Services > DynDNS 

![Menü: Services > DynDNS](https://ssv-comm.de/forum/bilder/938-services_3.png)

Ihr Gateway ermöglicht Anwendungen, in denen es selbst über einen DNS-Namen im Internet erreichbar sein muss. Ein Beispiel wäre der Betrieb als VPN-Server. Da ein solches Gateway in der Regel keine statische IP-Adresse im Internet erhält, lässt sich alternativ DynDNS nutzen.

DynDNS oder auch DDNS sind Abkürzungen für dynamisches DNS. Dahinter verbirgt sich eine Technik, um die IP-Adressen einzelner Services im Domain Name System (DNS) dynamisch zu aktualisieren. Der Zweck ist, dass ein Rechnersystem mit einem global erreichbaren Service nach dem Wechsel seiner IP-Adresse automatisch und schnell den dazugehörigen Eintrag im DNS ändert.

**DynDNS configuration:** Ein- und ausschalten des DynDNS-Service-Updates. Auswahl des DynDNS-Providers, bei dem ein entsprechender Account existiert, sowie des vollständigen Host-Namens (FQDN = Fully-Qualified Domain Name, also ein vollständiger Domain-Name). Des Weiteren lässt sich die Update-Periode einstellen.

**Change DynDNS username and password:** Unter dieser Überschrift lässt sich ein neues Passwort für einen Benutzernamen festlegen.

**Notification to webserver after IP address changes:** Ein- und ausschalten eines Benachrichtigungsdienstes für den Fall, dass sich die IP-Adresse des Gateways im Internet verändert hat.

## 4.4 Services > DHCP Server 

![Menü: Services > DHCP Server](https://ssv-comm.de/forum/bilder/938-services_4.png)

Das Gateway unterstützt die automatische IP-Adressvergabe per Dynamic Host Configuration Protocol (DHCP) an OT-Baugruppen (DHCP-Client-Baugruppen), die mit einer Gateway-LAN-Schnittstelle verbunden sind. Mit anderen Worten: Das Gateway lässt sich als DHCP-Server nutzen.

**Genral configuration:** Ein- und ausschalten des DHCP-Serverbetriebs.

**Address range:** Festlegen des IP-Adressbereichs, aus dem IP-Adressen per DHCP an die Client-Baugruppen vergeben werden. 

## 4.5 Services > SNMP 

![Menü: Services > SNMP](https://ssv-comm.de/forum/bilder/938-services_5.png)

Das Simple Network Management Protocol (SNMP) ist ein Netzwerkprotokoll, das von der IETF entwickelt wurde, um Gateways und andere Netzwerkbaugruppen von einem zentralen Managementsystem aus zu überwachen und bestimme Parameter verändern zu können. Das Protokoll regelt dabei die Kommunikation zwischen den überwachten Baugruppen und dem Managementsystem

**SNMP configuration:** Ein- und ausschalten des SNMP-Betriebs. Auswahl der SNMP-Version sowie weiterer Parameter.

## 4.6 Services > Remote Access 

![Menü: Services > Remote Access](https://ssv-comm.de/forum/bilder/938-services_6.png)

**OpenSSH configuration:** Es wird ein SSH-basierter Administratorenzugriff auf das Gateway unterstützt (SSH Secure Shell). Dafür läuft innerhalb des Gateway-Betriebssystems ein OpenSSH-Daemon (SSHD). Hier lässt sich der SSHD ein- und ausschalten sowie konfigurieren. Des Weiteren wird der aktuelle *RSA key fingerprint* angezeigt.  

**Change passwort for user "root":** Der SSH-Zugriff auf das Gateway erfolgt grundsätzlich mit Administratorenrechten (User „root“). Das Passwort für diesen Benutzer lässt sich hier ändern. 

## 4.7 Services > WebUI 

![Menü: Services > WebUI](https://ssv-comm.de/forum/bilder/938-services_7.png)

Das SSV/WebUI Ihres Gateways unterstützt zwei unterschiedliche Benutzerklassen: 1) einen Administrator (*admin*) mit allen Rechten und 2) einen Benutzer (*user*) mit eingeschränkten Rechten, dem auch nur eine einstellbare Selektivansicht des SSV/WebUI präsentiert wird.

**SSV/WebUI configuration:** In diesem Bereich lässt sich das gesamte WebUI ausschalten. Des Weiteren sind verschiedene Konfigurationseinstellungen möglich; z. B. die Wahl zwischen dem ungeschützten HTTP- oder dem sicheren HTTPS-Protokoll, die Auswahl des TCP-Ports für den HTTP- bzw. HTTPS-Zugriff sowie das Erscheinungsbild des SSV/WebUI.    

**Change admin access acount:** Ändern des Benutzernamen und Passwort für den WebUI-Zugriff mit Administratorenrechten (*admin*).

**Change user access acount:** Festlegen bzw. verändern des Benutzernamen und Passwort für den WebUI-Zugriff mit eingeschränkten Benutzerrechten (*user*).

## 5.1 Proxies > Web 

![Menü: Proxies > Web](https://ssv-comm.de/forum/bilder/938-proxies_1.png)

Wenn in den Automatisierungsbaugruppen eines OT-Netzwerks HTTP-Server existieren, lässt sich über die Web-Proxy-Funktion Ihres Gateways die IT-Sicherheit für den Zugriff auf diese Server steigern. Dazu wird für jeden HTTP-Server jeweils ein Web-Proxy konfiguriert, der das unsichere HTTP-Protokoll in das sichere HTTPS-Protokoll umwandelt. Es entsteht also ein HTTP-to-HTTPS-Proxy. Anschließend erfolgt der Browserzugriff eines externen Nutzers nicht mehr direkt auf den HTTP-Server in der Automatisierungsbaugruppe, sondern per HTTPS auf den Proxy im Gateway.  

**General configuration:** Die Web-Proxy-Funktion Ihres Gateways kann hier ein- und ausgeschaltet werden.

**Proxy redirection:** In diesem Bereich werden die einzelnen Web-Proxy-Verbindungen als Übersicht angezeigt. Jede einzelne Proxy-Verbindung lässt sich jeweils editieren und löschen.

**Create / edit a redirection entry:** Unter dieser Überschrift wird eine neue Web-Proxy-Verbindung erzeugt. Dafür sind jeweils die folgenden Eingaben erforderlich: 1.) die TCP-Portnummer für den *Listen on port*. 2.) Die IP-Adresse und die Portnummer für den *Relay to*-Part. Des Weiteren muss für einen HTTP-to-HTTPS-Proxy die *Encryption* (also die SSL- bzw. TLS-Funktion) explizit eingeschaltet werden. Ansonsten ergibt sich ein HTTP-to-HTTP-Proxy (also z. B. eine Portumleitung für den externen Webzugriff).

**SSL certificate:** für den HTTP-to-HTTPS-Proxy wird ein Zertikat benötigt. Dieses Zertifikat lässt sich hier erstellen.

## 5.2 Proxies > DNS 

![Menü: Proxies > DNS](https://ssv-comm.de/forum/bilder/938-proxies_2.png)

Ein DNS-Proxy leitet DNS-Anforderungen (DNS-Request) und DNS-Antworten (DNS-Response) zwischen DNS-Clients und einem DNS-Server weiter. Der DNS-Proxy vereinfacht das Netzwerkmanagement. Wenn sich z. B. die DNS-Serveradresse ändert, ist nur eine veränderte Konfiguration für den DNS-Proxy erforderlich, nicht aber für jeden einzelnen DNS-Client.

**General configuration:** Hier können Sie den DNS-Proxy-Service ein- und ausschalten.

## 5.3 Proxies > FTP 

![Menü: Proxies > FTP](https://ssv-comm.de/forum/bilder/938-proxies_3.png)

Wenn in den Automatisierungsbaugruppen eines OT-Netzwerks FTP-Server existieren, lässt sich über die FTP-Proxy-Funktion Ihres Gateways der Zugriff auf diese Server auf andere TCP-Ports umleiten.

**General configuration:** Die FTP-Proxy-Funktion Ihres Gateways kann hier ein- und ausgeschaltet werden.

**Proxy redirection:** In diesem Bereich werden die einzelnen FTP-Proxy-Verbindungen als Übersicht angezeigt. Jede einzelne Proxy-Verbindung lässt sich jeweils editieren und löschen.

**Create / edit a redirection entry:** Unter dieser Überschrift wird eine neue FTP-Proxy-Verbindung erzeugt. Dafür sind jeweils die folgenden Eingaben erforderlich: 1.) die TCP-Portnummer für den *Listen on port*. 2.) Die IP-Adresse und die Portnummer für den *Relay to*-Part.

## 5.4 Proxies > TCP 

![Menü: Proxies > TCP](https://ssv-comm.de/forum/bilder/938-proxies_4.png)

Ein TCP-Proxy erzeugt einen TCP-Socket unter einer vorgegebenen TCP-Portnummer (*Listen on port* socket) und erzeugt eine bidirektionale Datenverbindung zwischen diesem Socket und einem weiteren einstellbaren TCP-Socket (*Relay to* socket), der sich auf dem gleichen Gateway oder einem externen Rechnersystem mit einer statischen IP-Adresse befinden kann.

**General configuration:** Die TCP-Proxy-Funktion Ihres Gateways kann hier ein- und ausgeschaltet werden.

**Proxy redirection:** In diesem Bereich werden die einzelnen TCP-Proxy-Socket-Verbindungen als Übersicht angezeigt. Jede einzelne Socket-Verbindung lässt sich jeweils editieren und löschen.

**Create / edit a redirection entry:** Unter dieser Überschrift wird eine neue TCP-Proxy-Socket-Verbindung erzeugt. Dafür sind jeweils die folgenden Eingaben erforderlich: 1.) die TCP-Portnummer für den *Listen on port*. 2.) Die IP-Adresse und die Portnummer für den *Relay to*-Part.

## 5.5 Proxies > UDP 

![Menü: Proxies > UDP](https://ssv-comm.de/forum/bilder/938-proxies_5.png)

Ein UDP-Proxy erzeugt einen UDP-Socket unter einer vorgegebenen UPD-Portnummer (*Listen on port* socket) und erzeugt eine bidirektionale Datenverbindung zwischen diesem Socket und einem weiteren einstellbaren UDP-Socket (*Relay to* socket), der sich auf dem gleichen Gateway oder einem externen Rechnersystem mit einer statischen IP-Adresse befinden kann.

**General configuration:** Die UPD-Proxy-Funktion Ihres Gateways kann hier ein- und ausgeschaltet werden.

**Proxy redirection:** In diesem Bereich werden die einzelnen UDP-Proxy-Socket-Verbindungen als Übersicht angezeigt. Jede einzelne Socket-Verbindung lässt sich jeweils editieren und löschen.

**Create / edit a redirection entry:** Unter dieser Überschrift wird eine neue UDP-Proxy-Socket-Verbindung erzeugt. Dafür sind jeweils die folgenden Eingaben erforderlich: 1.) die UDP-Portnummer für den *Listen on port*. 2.) Die IP-Adresse und die Portnummer für den *Relay to*-Part.

## 6.1 Apps > Node-RED 

![Menü: Apps > Node-RED](https://ssv-comm.de/forum/bilder/938-apps_1.png)

Einige nachträglich installierbare Gateway-Apps erzeugen unter der Menüleistenfunktion *Apps* eigene Einträge, um dem Benutzer eine Konfigurations-Webseite zur Verfügung zu stellen. Die hier dargestellte Abbildung zeigt als Beispiel die Konfigurationsseite der Node-RED-App. 

**General configuration:** Die Node-RED lässt sich ein- und ausschalten. Ist Node-RED eingeschaltet, läuft die Software dauerhaft als Prozess im Linux-Betriebssystem des Gateways und wird auch bei jedem Bootvorgang automatisch gestartet. Alle unter Node-RED erzeugten Flows werden automatisch zur Ausführung gebracht. Darüber hinaus lassen sich die auf einem Gateway unter Node-RED erzeugten Flow hier in eine Datei auf dem PC exportieren und auf einem anderem Gateway wieder importieren. Zusätzlich kann für den Speicherbereich mit den Node-RED-Flow ein manueller *Cleanup* erzeugt werden (Löschen aller Flow-Komponenten).

**Access protection:** Node-RED besitzt eine Web-basierte Oberfläche, die ein weiteres Browserfenster benötigt. Der Zugriff auf die Node-RED-Oberfläche lässt sich über eine Benutzeranmeldung mit Benutzername/Passwort schützen. Der Benutzername und das Passwort lassen sich hier einstellen. Des Weiteren kann der Webbrowser entweder über eine ungesicherte HTTP- oder eine geschützte HTTPS-Verbindung auf die Node-RED-Oberfläche zugreifen. Auch diese Eigenschaft ist hier einstellbar. 
