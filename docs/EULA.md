##  Corona-Warn-App TEST
# Nutzungsbedingungen
## Inhalt
1. Welche Funktionen hat die App?
2. Was bedeutet niedriges oder erhöhtes Risiko?
3. Risiko-Begegnung – was tun?
4. Kein Infektionsschutz durch die App
5. Abrufen von Testergebnissen
6. Auslösen einer Warnung
7. Voraussetzungen für die Nutzung der App
8. Grenzen der App
9. Nutzungsrechte
10. Wichtige Hinweise zu Verfügbarkeit und Änderungen
11. Keine Gewährleistung
12. Besondere Bedingungen für die iOS-Version der App
13. Schlussbestimmungen

***


Herausgeber der App ist das

> Robert Koch-Institut
>
> Nordufer 20
>
> 13353 Berlin ("**RKI**")

vertreten durch den Präsidenten. Für Fragen, Beschwerden und Ansprüche im Zusammenhang mit diesen Nutzungsbedingungen können Sie das RKI per E-Mail unter [https://www.CoronaWarnApp@rki.de](https://www.coronawarn.de) erreichen.

Bitte lesen Sie diese Nutzungsbedingungen sorgfältig. Diese Nutzungsbedingungen regeln Ihre Nutzung der Corona-Warn-App einschließlich der Nutzung zukünftiger Versionen (Patches, Updates und Upgrades) ("**App**") und der Nutzung weiterer Dienste ("**CWA-Dienste**"), die derzeit oder zukünftig vom RKI im Zusammenhang mit der App bereitgestellt werden. Sie können diese Nutzungsbedingungen jederzeit in der App unter „App-Informationen“ und unter [https://www.coronawarn.app/assets/documents/cwa-eula-de.pdf](https://www.coronawarn.app/assets/documents/cwa-eula-de.pdf) abrufen. Die separate Datenschutzerklärung (siehe unter „App-Informationen“ und unter [https://www.coronawarn.app/assets/documents/cwa-privacy-notice-de.pdf](https://www.coronawarn.app/assets/documents/cwa-privacy-notice-de.pdf) ist nicht Bestandteil dieser Nutzungsbedingungen. Bitte lesen Sie dennoch auch die Datenschutzerklärung sorgfältig.

Die App ist für die Nutzung auf iOS-Geräten im Apple App Store verfügbar und für die Nutzung auf Android-Geräten bei Google Play. Allgemeine Nutzungsbedingungen für Applikationen von Apple oder Google finden im Verhältnis zum RKI keine Anwendung. Das RKI ist allein verantwortlich für die Inhalte der App sowie deren Wartung und Pflege und für Ansprüche, die Sie ggf. in Bezug auf die App haben.

Mit der Installation und Nutzung der App erklären Sie sich mit diesen Nutzungsbedingungen einverstanden. Sollten Sie mit den Nutzungsbedingungen nicht einverstanden sein, dürfen Sie die App nicht installieren oder nutzen (bzw. müssen diese wieder löschen) und dürfen auch die die damit verbundenen Dienste und Systeme nicht nutzen. Etwaige Rechte unter Open Source-Lizenzen in Bezug auf den Quellcode der App bleiben hiervon unberührt.

Sie sind für die Einhaltung dieser Nutzungsbedingungen auch dann verantwortlich, wenn Sie das Endgerät, auf dem Sie die App installiert haben, Dritten überlassen und diese die App verwenden.

Die App richtet sich an Personen, die mindestens 16 Jahre alt sind.

## 1.	WELCHE FUNKTIONEN HAT DIE APP?
Ziel der App ist es, SARS-CoV-2-Infektionsketten frühzeitig zu durchbrechen. Personen sollen möglichst zuverlässig und schnell über Begegnungen mit infizierten Personen und damit mögliche Übertragungen des Virus informiert werden, damit sie sich freiwillig isolieren können, um damit zu einer Eindämmung der SARS-CoV-2-Pandemie beizutragen.

Die App nutzt das von Apple und Google bereitgestellte System für COVID-19-Begegnungsbenachrichtigungen („**COVID-19-Benachrichtigungssystem**“), das integraler Bestandteil des Betriebssystems Ihres Endgeräts ist. Der genaue Name, die Bedienung und der Funktionsumfang des COVID-19-Benachrichtigungssystems können je nach Hersteller und Version Ihres Betriebssystems variieren. Das COVID-19-Benachrichtigungssystem ist kein Bestandteil der CWA-Dienste oder der App, sondern eine Systemanforderung der App. Für die Verfügbarkeit, Funktionsfähigkeit, Zuverlässigkeit und die Nutzungsbedingungen und Datenverarbeitung des COVID-19-Benachrichtigungssystems ist der Anbieter des jeweiligen Betriebssystems verantwortlich. Das RKI hat hierauf keinen Einfluss.

Die wesentlichen Funktionen der App sind nachstehend beschrieben. Hierbei handelt es sich um eine Beschreibung zu Ihrer Information und nicht um eine Beschaffenheitsvereinbarung oder die Vereinbarung bestimmter Funktionen, bitte beachten Sie die diesbezüglichen Hinweise und Vorbehalte unter Ziffer 10.

<em>Risiko-Ermittlung</em>

Nachdem Sie das COVID-19-Benachrichtigungssystem Ihres Betriebssystems und die Risiko-Ermittlung in der App aktiviert haben, beginnt das COVID-19-Benachrichtigungssystem mit der Aussendung von Zufalls-IDs über die Bluetooth-Schnittstelle Ihres Geräts. Zugleich empfängt das COVID-19-Benachrichtigungssystem die Zufalls-IDs von anderen Nutzern und speichert diese zusammen mit für die Bestimmung des Infektionsrisikos relevanten technischen Informationen zur Bluetooth-Signalstärke (je stärker das Signal, desto geringer ist in der Regel der Abstand), zum Tag und zur Dauer der Begegnung.

In regelmäßigen Abständen holt sich die App über die CWA-Dienste eine Liste der Zufalls-IDs der Personen, die sich in der offiziellen Corona-App eines am länderübergreifenden Warnsystem teilnehmenden Landes infiziert gemeldet haben, und übergibt diese an das COVID-19-Benachrichtigungssystem. Das COVID-19-Benachrichtigungssystem vergleicht diese mit den gespeicherten Zufalls-IDs im Gerät, um eine Risiko-Begegnung zu ermitteln.

<em>Infektionsrisiko</em>

Bei einer vom COVID-19-Benachrichtigungssystem festgestellten Risiko-Begegnung mit einer positiv getesteten Person informiert das COVID-19-Benachrichtigungssystem die App und übergibt ihr die Aufzeichnungen zur Signalstärke, zum Tag und zur Dauer des Kontakts. Die App bewertetet diese Aufzeichnungen und informiert Sie dann über das für Sie ermittelte Infektionsrisiko und entsprechende Handlungsempfehlungen des RKI. Hier kann zum Beispiel die Kontaktaufnahme mit ärztlichem Fachpersonal, mit dem zuständigen Gesundheitsamt und/oder die freiwillige häusliche Isolation empfohlen werden.

<em>Testregistrierung</em>

Ab dem Zeitpunkt der Probenabgabe für einen Test auf eine SARS-CoV-2-Infektion können Sie über die App den digitalen Testinformationsprozess starten und damit über das Testergebnis benachrichtigt werden. Voraussetzung ist, dass das Testlabor an die CWA-Dienste angeschlossen ist und Ihnen einen QR-Code oder eine TAN für die Testregistrierung aushändigt. Die App übermittelt lediglich das vom jeweiligen Labor mitgeteilte Testergebnis. Das RKI ist weder für die Durchführung des Tests noch für den Inhalt des Testergebnisses verantwortlich.

<em>Andere warnen</em>

Im Fall eines positiven SARS-CoV-2-Befunds können Sie die im COVID-19-Benachrichtigungssystem gespeicherten eigenen Zufalls-IDs der letzten 14 Tage sowie optionale Angaben zum erstmaligen Auftreten von eventuellen Krankheitssymptomen an die CWA-Dienste übermitteln, damit andere Personen, die die offizielle Corona-App eines am länderübergreifenden Warnsystem teilnehmenden Landes nutzen, auf ihrem eigenen Smartphone benachrichtigt werden können, falls sie mit Ihnen eine Risiko-Begegnung hatten.

<em>Technische Beschreibung der App</em>

Die technischen Funktionen der App sowie der damit verbundenen Dienste und Systeme sind unter folgendem Link detailliert beschrieben:

[https://github.com/Corona-Warn-App](https://github.com/Corona-Warn-App)

Diese technische Beschreibung dient lediglich der Erläuterung und ist nicht Bestandteil dieser Nutzungsbedingungen. Sie stellt auch keine Beschaffenheitsvereinbarung in Bezug auf die App dar.

<em>Weiterführende Informationen</em>

Weiterführende Informationen zur App finden Sie unter folgendem Link: [https://www.coronawarn.app/de](https://www.coronawarn.app/de)  (Anbieter: SAP Deutschland SE & Co. KG)

Weiterführende Informationen zur SARS-CoV-2-Pandemie finden Sie unter folgendem Link: [https://www.zusammengegencorona.de](https://www.zusammengegencorona.de) (Anbieter: Bundesministerium für Gesundheit)

Diese weiterführenden Informationen dienen lediglich der Erläuterung und sind nicht Bestandteil dieser Nutzungsbedingungen.

## 2.	WAS BEDEUTET NIEDRIGES ODER ERHÖHTES RISIKO?

Die App berechnet auf Basis der vom COVID-19-Benachrichtigungssystem aufgezeichneten Begegnungen ein geschätztes individuelles Risiko. Hierbei werden Faktoren wie der Zeitraum seit der Begegnung, die Dauer der Begegnung, die ungefähre Nähe zur Corona-positiv getesteten Person, basierend auf der gemessenen Dämpfung des Bluetooth-Signals sowie die Dauer seit Symptombeginn (sofern von der Corona-positiv getesteten Person beim Bereitstellen der Zufalls-IDs angegeben) berücksichtigt.

Auf dieser Basis wird Ihnen in der App ein „niedriges“, „erhöhtes“ oder – wenn keine Risiko-Ermittlung durchgeführt werden kann – „unbekanntes Risiko" angezeigt. Es handelt sich hierbei um eine Schätzung auf der Grundlage der vom COVID-19-Benachrichtigungssystem und den CWA-Diensten bereitgestellten Daten. **Eine Aussage über das Vorliegen einer tatsächlichen Infektion mit SARS-CoV-2 ist hiermit nicht verbunden.** Auch bei der Angabe eines "niedrigen Risikos" kann eine Infektion vorliegen, während auch bei Angabe eines "erhöhten Risikos" eine Infektion nicht gegeben sein kann.

**Andere Faktoren können Ihr persönliches Infektionsrisiko erheblich beeinflussen. Diese werden von der App nicht berücksichtigt.** Das sind insbesondere Ihre persönlichen Umstände, die äußeren Umstände einer Risiko-Begegnung mit einer infizierten Person, Ihr persönliches Verhalten sowie Begegnungen mit Dritten, die von der App nicht erfasst wurden. Bitte beachten Sie die Hinweise in Ziffer 4.

## 3.	RISIKO-BEGEGNUNG – WAS TUN?

Wenn Sie über die App über eine festgestellte Risiko-Begegnung mit Corona-positiv getesteten Personen informiert werden, erhalten Sie verhaltensbezogene Empfehlungen. Diese Empfehlungen sind rechtlich nicht verbindlich, ihre Befolgung wird aber vom RKI empfohlen. Gesetzliche und vertragliche Pflichten sowie behördliche Anordnungen für den Fall einer Risiko-Begegnung mit infizierten Personen bleiben unberührt und müssen von Ihnen unabhängig von diesen Empfehlungen befolgt werden.

**Innerhalb oder über die App erfolgt keinerlei medizinische Diagnose.**

**Die Information über eine Risiko-Begegnung bedeutet nicht, dass Sie sich mit SARS-CoV-2 infiziert haben.** Sie besagt lediglich, dass sie während der letzten 14 Tage eine Risiko-Begegnung mit einer anderen Person hatten, bei der eine SARS-CoV-2-Infektion positiv festgestellt wurde. Hieraus ergibt sich für Sie zunächst nur eine Möglichkeit, dass Sie sich ebenfalls infiziert haben könnten. Die Einstufung des diesbezüglichen Risikos als "niedrig" oder "erhöht" erfolgt allein auf der Basis der vom COVID-19-Benachrichtigungssystem und den CWA-Diensten (z. B. Angaben zum Symptombeginn) bereitgestellten Daten und lässt keine Aussage über das tatsächliche Vorliegen einer Infektion zu.

**Die Information über eine Risiko-Begegnung kann unzutreffend sein.** Die Risiko-Begegnung kann vom COVID-19-Benachrichtigungssystem beispielsweise zu einem Zeitpunkt aufgezeichnet worden sein, zu dem Sie sich nicht in der Nähe Ihres Smartphones aufgehalten haben oder während eine andere Person Ihr Smartphone verwendet hat. Die Risiko-Begegnung kann auch aufgrund bestehender Grenzen des COVID-19-Benachrichtigungssystems fälschlicherweise registriert worden sein (siehe unten Ziffer 8).

## 4.	KEIN INFEKTIONSSCHUTZ DURCH DIE APP

Die App dient der Unterbrechung von Infektionsketten.

+ **Die App schützt Sie nicht vor einer SARS-CoV-2-Infektion.**
+ **Die App reduziert Ihr persönliches Infektionsrisiko nicht.**
+ **Sie können sich auch mit SARS-CoV-2 infizieren, ohne dass die App Sie über die Risiko-Begegnung mit der Person informiert, die Sie infiziert hat:**

   * Die App kennt nicht alle Ihre Begegnungen mit anderen Personen, z.B. weil andere Personen die App nicht verwenden, Sie Ihr Smartphone nicht immer bei sich tragen oder die App nicht immer in Betrieb haben oder weil die Begegnungsaufzeichnung mit dem COVID-19-Benachrichtigungssystem gewissen Grenzen unterliegt (siehe unten Ziffer 8).

   * Die App informiert Sie nur über vom COVID-19-Benachrichtigungssystem festgestellte und an die App weitergegebene Risiko-Begegnungen mit infizierten Personen. Das setzt voraus, dass die infizierte Person eine Warnung über die App auslöst. Das Auslösen der Warnung ist freiwillig und erfolgt möglicherweise nicht durch alle infizierten Personen.


   Bitte halten Sie auch bei Verwendung der App die sonstigen Vorsichtsmaßnahmen und behördlichen Anordnungen ein. Verlässliche Informationen über die SARS-CoV-2-Pandemie und Vorsichtsmaßnahmen finden Sie unter anderem auf:

   [https://www.infektionsschutz.de/coronavirus](https://www.infektionsschutz.de/coronavirus) (Anbieter: Bundeszentrale für gesundheitliche Aufklärung)

   [https://www.zusammengegencorona.de](https://www.zusammengegencorona.de) (Anbieter: Bundesministerium für Gesundheit)

   [https://www.rki.de/covid-19](https://www.rki.de/covid-19) (Anbieter: RKI)

   Diese weiterführenden Informationen dienen lediglich Ihrer Information und sind nicht Bestandteil dieser Nutzungsbedingungen.

   Halten Sie sich auch bei Verwendung der App an die **AHA-Regeln**:

  **A**	 - 	Halten Sie mindestens 1,5m Abstand zu Ihren Mitmenschen

  **H** 	- 	Waschen Sie sich regelmäßig für mindestens 20 Sekunden die Hände

  **A**	- 	Tragen Sie beim Einkauf und in öffentlichen Verkehrsmitteln eine Alltagsmaske

  So schützen Sie sich selbst und andere vor dem Virus.


## 5.	ABRUFEN VON TESTERGEBNISSEN
Sie dürfen über die App ausschließlich Ihre eigenen Testergebnisse abrufen.

Wenn Sie auf Testergebnisse warten und die CWA-Dienste nicht zur Verfügung stehen oder der Abruf der Testergebnisse über die App aus sonstigen Gründen nicht funktioniert, dann informieren Sie sich bitte über andere Kontaktwege über das Testergebnis, z.B. über die jeweilige Teststelle wie Ihren Hausarzt oder das örtliche Gesundheitsamt. Warten Sie nicht darauf, dass die App wieder zur Verfügung steht.

## 6.	AUSLÖSEN EINER WARNUNG
Sie können über die App andere Kontaktpersonen warnen, wenn Sie positiv auf eine Infektion mit SARS-CoV-2 getestet wurden. **Sie dürfen diese Warnung nur auslösen, wenn die Infektion durch einen Test in einem zugelassenen Testlabor positiv bestätigt wurde**.


Falls Ihr Testlabor noch nicht an die CWA-Dienste angeschlossen ist, erfolgt eine Überprüfung Ihres Infektionsstatus über eine vom RKI eingerichtete Verifikations-Hotline. Das Auslösen einer Warnung über die App auf der Grundlage einer bloßen Risiko-Mitteilung ist nicht zulässig.

<em>Bei Unsicherheit: erst Hausarzt oder Gesundheitsamt kontaktieren</em>

Wenn Sie nicht sicher sind, ob Sie sich infiziert haben oder nicht, dann kontaktieren Sie bitte Ihren Hausarzt oder das zuständige Gesundheitsamt. Hier erhalten Sie weitere Beratung und können sich erforderlichenfalls auf eine Infektion testen lassen. In der Zwischenzeit befolgen Sie die allgemein gültigen Empfehlungen für das Verhalten bei dem Verdacht einer SARS-CoV-2-Infektion.

<em>Missbrauchsverbot</em>

**Das missbräuchliche Auslösen einer Warnung ist untersagt und kann schwerwiegende Konsequenzen nach sich ziehen.** Insbesondere können Sie sich eventuell gegenüber anderen betroffenen Personen schadenersatzpflichtig machen.

## 7.	VORAUSSETZUNGEN FÜR DIE NUTZUNG DER APP
Folgende technische Voraussetzungen sind für die Nutzung der App erforderlich:

<em>Sie benötigen eine Datenverbindung</em>

Bestimmte Funktionen der App setzen auf zentrale Dienste und Systeme auf, die über die CWA-Dienste zur Verfügung gestellt werden. Diese Funktionen stehen daher nur zur Verfügung, wenn Ihr Smartphone über eine Datenverbindung mit dem Internet verfügt, z.B. über UMTS, LTE oder WLAN, um hierüber auf die CWA-Dienste zugreifen zu können. Ohne Datenverbindung stehen einige oder alle Funktionen der App nicht zur Verfügung. Dies gilt auch, wenn Sie Ihr Smartphone in den Flugmodus versetzen oder ausschalten.

<em>Das COVID-19-Benachrichtigungssystem muss aktiviert sein</em>

Das COVID-19-Benachrichtigungssystem Ihres Smartphones muss aktiviert und für die Region „Deutschland“ bzw. die App freigegeben sein.

<em>Hintergrundaktualisierung</em>

Die App muss dauerhaft im Hintergrundbetrieb laufen. Wenn Sie das Smartphone neu starten (z.B. nach dem Ausschalten, nachdem die Batterie leer war oder nach einem Update des Betriebssystems) oder nach einer erzwungenen Beendigung der App müssen Sie auch die App neu starten.

<em>Einstellungen auf dem Smartphone</em>

Für die Nutzung der App müssen Sie ferner die Bluetooth (BLE)-Funktionen auf Ihrem Smartphone aktivieren und ggf. zur Verwendung durch die App freigegeben.

Für die Nutzung der App empfiehlt das RKI ferner folgende Funktionen auf Ihrem Smartphone zu aktivieren und ggf. zur Verwendung durch die App freizugegeben, auch wenn diese nicht Voraussetzung für die Nutzung der grundlegenden Funktionen der App sind:

* Benachrichtigungen
* Kamerafunktio

Bitte prüfen Sie in den Einstellungen ihres Smartphones, ob diese Funktionen aktiviert und für die Verwendung der App freigegeben sind.

Eine ausführliche Anleitung zur Einrichtung der App unter iOS und Android finden Sie auf der Website des Open-Source-Projekts für die Corona-Warn-App unter [https://www.coronawarn.app/de](https://www.coronawarn.app/de) (Anbieter: SAP Deutschland SE & Co. KG). Die Anleitung dient lediglich der Erläuterung und ist nicht Teil dieser Nutzungsbedingungen.

<em>Sie müssen immer eine aktuelle Version der App verwenden</em>

Das RKI wird von Zeit zu Zeit Updates der App zur Verfügung stellen. Sie sollten diese Updates unverzüglich installieren und immer die neueste verfügbare Version der App verwenden. Beim Verwenden älterer Versionen kann es zu Fehlfunktionen und Störungen kommen. Sofern ein Update zwingend erforderlich ist, werden Sie beim Öffnen der App darauf hingewiesen.

<em>Sie benötigen aktuelle Versionen von iOS bzw. Android</em>

Die App verwendet das eigens von Apple in iOS und Google in Android implementierte COVID-19-Benachrichtigungssystem. Dieses steht in iOS erst ab Version 13.5 und in Android erst ab Version 6 zur Verfügung. Die App funktioniert daher leider nicht mit früheren Versionen der beiden Betriebssysteme.

## 8.	GRENZEN DER APP
Die App kann Sie dabei unterstützen, Risiko-Begegnungen mit anderen Nutzern zu erkennen, die später positiv getestet wurden. Die App hat aber auch Grenzen, die berücksichtigt werden müssen, insbesondere:

* Die App kann nur die vom COVID-19-Benachrichtigungssystem Ihres Betriebssystems aufgezeichneten und an die App weitergegebenen Risiko-Begegnungen bewerten. Die Verfügbarkeit, Vollständigkeit, Richtigkeit und Zuverlässigkeit dieser Aufzeichnungen im COVID-19-Benachrichtigungssystem können vom RKI nicht beeinflusst werden.

* Die App kann Sie nur vor Risiko-Begegnungen mit Corona-positiv getesteten Nutzern einer offiziellen Corona-App eines am länderübergreifenden Warnsystem teilnehmenden Landes warnen, die ihr positives Testergebnis über die jeweilige Corona-App für die länderübergreifende Warnfunktion zur Verfügung gestellt haben.

* Für die Bewertung des Infektionsrisikos nutzt die App die Aufzeichnungen zur Dämpfung des Bluetooth-Signals. Eine geringere Dämpfung bedeutet dabei grundsätzlich, dass das andere Smartphone näher ist. Eine höhere Dämpfung kann entweder bedeuten, dass das andere Smartphone weiter entfernt ist (also eine Entfernung von mehr als zwei Metern) oder dass sich zwischen den beiden Smartphones etwas befindet, was das Signal blockiert. Das können Objekte wie eine Wand oder eine Tasche, in der sich das Smartphone befindet, sein, aber genauso Personen oder Tiere.

## 9.	NUTZUNGSRECHTE
<em>Einfaches Nutzungsrecht</em>

Hiermit wird Ihnen eine eingeschränkte, nicht ausschließliche, nicht übertragbare, nicht unterlizenzierbare, widerrufliche Lizenz zur Nutzung der App für Ihre persönlichen, nicht kommerziellen Zwecke gewährt.

Die Lizenz für die iOS-Version der App umfasst die Nutzung auf jedem Apple-Gerät, an dem Sie Eigentum haben oder über das Sie Kontrolle ausüben, im Rahmen der geltenden Nutzungsbedingungen des App Stores, wobei auch über andere Apple Accounts, die mit Ihrem Apple Account via Family Sharing oder Volumenkauf verbunden sind, auf die App zugegriffen und diese genutzt werden kann.

Sie dürfen im Rahmen von Datensicherungen Kopien der App anfertigen. Darüberhinausgehende Rechte an der App werden Ihnen nicht eingeräumt.

<em>Eigentum an der App</em>

Die App ist das alleinige und ausschließliche Eigentum von SAP SE, Dietmar-Hopp-Allee 16, 69190 Walldorf („**SAP**“) oder deren Lizenzgebern, vorbehaltlich der Ihnen nach Ziffer 9 eingeräumten Rechte sowie sonstiger Rechte an der App, die SAP der Bundesrepublik Deutschland vertraglich eingeräumt hat.

<em>Open Source-Lizenzhinweise</em>

Information über die Verwendung von Drittkomponenten in der App und die anwendbaren Lizenzbestimmungen finden Sie in den Open Source-Lizenzhinweisen in der App.

Der Quellcode der App ist unter den Lizenzbedingungen der „Apache 2.0 License“ veröffentlicht und kann unter "[https://github.com/Corona-Warn-App](https://github.com/Corona-Warn-App)" heruntergeladen werden. Die Lizenzbedingungen der „Apache 2.0 License“ sind unter "[https://www.apache.org/licenses/LICENSE-2.0](https://www.apache.org/licenses/LICENSE-2.0)" abrufbar.

<em>Was nicht erlaubt ist</em>

Sie dürfen die App nicht manipulieren oder verändern.

Sie dürfen die App und die Schnittstellen zu den CWA-Diensten nicht missbräuchlich verwenden. Sie dürfen die CWA-Dienste nicht für andere Zwecke nutzen als den bestimmungsgemäßen Betrieb der App auf Ihrem Smartphone. Sie dürfen auf die CWA-Dienste ausschließlich über die App zugreifen.

## 10.	WICHTIGE HINWEISE ZU VERFÜGBARKEIT UND ÄNDERUNGEN
<em>Kein Anspruch auf bestimmte Funktionalität</em>

Die App wird Ihnen so zur Verfügung gestellt, wie sie vom RKI herausgegeben wird. Das RKI übernimmt keine Gewähr für die Funktionsfähigkeit der App oder der CWA-Dienste und vereinbart mit Ihnen keine bestimmte Beschaffenheit. Sie haben keinen Anspruch auf eine bestimmte Funktionalität oder anderweitige Beschaffenheit der App oder der CWA-Dienste. Das RKI kann die App jederzeit ändern und Funktionen ganz oder teilweise entfernen oder die App um zusätzliche Funktionen erweitern.

<em>Keine Verfügbarkeitszusage</em>

Das RKI kann den Betrieb der App und der CWA-Dienste jederzeit einschränken oder einstellen. Es besteht Ihrerseits kein Anspruch auf die weitergehende Verfügbarkeit der App oder der damit verbundenen Dienste und Systeme einschließlich der CWA-Dienste, weder in Bezug auf einzelne Funktionen noch in Bezug auf das System als Ganzes.

Das RKI macht keine Zusagen über die Verfügbarkeit oder Leistungsfähigkeit der CWA-Dienste. Diese können aufgrund von Wartungsarbeiten oder Störungen vorübergehend und ggf. auch für längere Zeiträume nicht zur Verfügung stehen. In diesen Fällen ist die Funktionalität der App ganz oder teilweise eingeschränkt.

<em>Änderung der Nutzungsbedingungen</em>

Das RKI behält sich vor, diese Nutzungsbedingungen zu ändern. Wenn Sie den geänderten Nutzungsbedingungen nicht zustimmen, können Sie die App und die CWA- Dienste nicht mehr nutzen und müssen die App von Ihrem Smartphone löschen.

<em>Änderung der Parameter der Risikobewertung</em>

Das RKI behält sich ferner vor, die im Rahmen der Bewertung des Infektionsrisikos verwendeten Parameter jederzeit zu ändern, um dadurch jeweils aktuellen Forschungsergebnissen zur Virusübertragung zu entsprechen. Das RKI bestimmt die verwendeten Parameter jeweils nach seinem Ermessen.

## 11.	KEINE GEWÄHRLEISTUNG
Das RKI bestimmt die Funktionen der App und der CWA-Dienste sowie deren Ausgestaltung. Das RKI vereinbart mit Ihnen keine bestimmte Beschaffenheit und Sie haben keinen Anspruch darauf, dass die App bestimmte Funktionen hat oder diese in bestimmter Weise ausgestaltet sind. Die App wird in dem Zustand und mit den Funktionen zur Verfügung gestellt, wie sie beim Veröffentlichen der App im Apple App Store oder bei Google Play durch das RKI implementiert sind.

Das RKI wird die App mit angemessener Sorgfalt zur Verfügung stellen und angemessene Sorgfalt hinsichtlich der CWA-Dienste anwenden. Das RKI gibt keine sonstigen Versprechen oder Zusicherungen im Hinblick auf die App oder die CWA-Dienste ab und gewährleistet insbesondere nicht, dass:

* Ihre Nutzung der App oder der CWA-Dienste ohne Unterbrechung möglich oder fehlerfrei sein wird,

* die App oder die CWA-Dienste frei von Verlusten, Korruption, Angriffen, Viren, Eingriffen, Hacking oder anderen sicherheitsrelevanten Störungen sein werden.

Für die Datensicherung Ihres Smartphones sowie ggf. damit verbundener Systeme sind Sie verantwortlich, inklusive der Datensicherung sämtlicher anderer Apps, welche auf Ihrem Smartphone gespeichert sind.

## 12.	BESONDERE BEDINGUNGEN FÜR DIE IOS-VERSION DER APP
Die folgenden Bedingungen gelten für den Bezug der App über den Apple App Store und die Nutzung der App unter dem Betriebssystem iOS.

<em>Wartung und Support</em>

Das RKI ist als Herausgeber der App allein verantwortlich für Wartung und Support der App nach Maßgabe dieser Nutzungsbedingungen. Apple übernimmt keinerlei Verpflichtung zur Erbringung irgendwelcher Wartungs- und Supportleistungen in Bezug auf die App.

<em>Keine Haftung von Apple für Störungen</em>

Im Fall von Störungen der App steht es Ihnen frei, Apple hierüber zu informieren. Soweit gesetzlich zulässig hat Apple keine weitergehenden Pflichten wegen Störungen der App.

<em>Produkthaftung</em>

Apple ist nicht verantwortlich für etwaige Ansprüche Ihrerseits oder von Dritten in Bezug auf die App oder deren Besitz oder Verwendung einschließlich

* Ansprüchen wegen Produkthaftung,
* Ansprüchen auf der Basis, dass die App anwendbare gesetzliche oder regulatorische Anforderungen nicht erfüllt und
* Ansprüchen unter Verbrauchschutz- und Datenschutzgesetzen oder ähnlichen Gesetzen,

einschließlich im Zusammenhang mit der Nutzung der HealthKit- und HomeKit-Frameworks.

<em>Verletzung von Schutzrechten Dritter</em>

Für den Fall, dass Dritte Ansprüche wegen der Verletzung von Schutzrechten durch die App oder den Besitz oder die Verwendung der App durch Sie geltend machen, ist Apple nicht verantwortlich für Untersuchungen, Verteidigung, Beilegung oder Erfüllung solcher Ansprüche wegen der Verletzung von Schutzrechten.

<em>US Embargos und Sanktionen</em>

Mit Anerkennen dieser Nutzungsbedingungen bestätigten Sie,

* dass Sie sich nicht in einem Land aufhalten, das einem Embargo der Regierung der Vereinigten Staaten von Amerika unterliegt oder von der Regierung der Vereinigten Staaten von Amerika als Unterstützer von Terroristen ("<em>terrorist supporting" country</em>) designiert wurde und
* dass Sie nicht auf einer Liste der Regierung der Vereinigten Staaten von Amerika als sog. Prohibited or Restricted Party geführt werden.

<em>Drittbegünstigung von Apple</em>

Sie erkennen an und erklären sich damit einverstanden, dass Apple ein Drittbegünstigter unter diesen Nutzungsbedingungen ist und Apple daher diese Nutzungsbedingungen Ihnen gegenüber durchsetzen kann. Die Änderung und Aufhebung dieser Nutzungsbedingungen einschließlich der Rechte von Apple hierunter bleibt den Vertragsparteien vorbehalten und bedarf nicht der Zustimmung von Apple.

## 13.	SCHLUSSBESTIMMUNGEN
<em>Bestimmungsgemäße Nutzung / Sperrung bei missbräuchlicher Verwendung</em>

Sie dürfen die App und die CWA-Dienste nur bestimmungsgemäß nutzen. Das RKI behält sich vor, Sie bei missbräuchlicher Verwendung der App oder nicht bestimmungsgemäßem Zugriff auf die CWA-Dienste von der Nutzung der App und der CWA-Dienste auszuschließen.

<em>Bestimmungsgemäße Nutzung / Sperrung bei missbräuchlicher Verwendung</em>

Sie dürfen die App und die CWA-Dienste nur bestimmungsgemäß nutzen. Das RKI behält sich vor, Sie bei missbräuchlicher Verwendung der App oder nicht bestimmungsgemäßem Zugriff auf die CWA-Dienste von der Nutzung der App und der CWA-Dienste auszuschließen.

<em>Dienste Dritter</em>

Sofern Sie im Zusammenhang mit der Nutzung der App Dienste Dritter in Anspruch nehmen, insbesondere die Dienste von Telekommunikationsdienstleistern für die Bereitstellung einer Datenverbindung, sind Sie für damit im Zusammenhang stehenden Kosten und die Einhaltung der jeweiligen Vertragsbedingungen selbst verantwortlich.

<em>Anwendbares Recht</em>

Diese Nutzungsbedingungen unterliegen dem Recht der Bundesrepublik Deutschland. Das Übereinkommen der Vereinten Nationen über Verträge über den internationalen Warenkauf findet keine Anwendung. Die gesetzlichen Vorschriften zur Beschränkung der Rechtswahl und zur Anwendbarkeit zwingender Vorschriften insbesondere des Staates, in dem Sie als Verbraucher Ihren gewöhnlichen Aufenthalt haben, bleiben unberührt.

<em>Teilunwirksamkeit</em>

Diese Nutzungsbedingungen bleiben auch bei rechtlicher Unwirksamkeit einzelner Punkte in ihren übrigen Teilen verbindlich. Anstelle der unwirksamen Punkte treten, soweit vorhanden, die gesetzlichen Vorschriften. Soweit dies für eine Vertragspartei eine unzumutbare Härte darstellen würde, werden die Nutzungsbedingungen jedoch im Ganzen unwirksam.

***
