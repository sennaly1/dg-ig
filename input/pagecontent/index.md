<!--
  Schritt 7: Startseite eures IG
  Ersetzt die TODOs durch eigenen Text. Markdown ist erlaubt.
  Diese Seite ist die erste, die man auf GitHub Pages sieht.
-->

### Use Case
Eine Hausarztpraxis erfasst Arzneimittelallergien ihrer Patientinnen und Patienten strukturiert in einem FHIR-System. Die Informationen werden von einer Ärztin oder einem Arzt dokumentiert und können von einer Notfallstation ausgelesen werden. Dadurch stehen wichtige Angaben zu Allergien und möglichen Reaktionen bei einer Notfallbehandlung zur Verfügung.

### Scope

Dieser Implementation Guide definiert ein FHIR-Profil auf Basis von CH Core AllergyIntolerance zur Erfassung von Arzneimittelallergien. Er legt Anforderungen an den klinischen Status, die Codierung, die Gefährlichkeit, den Beginn, die erfassende Person und allergische Reaktionen fest. Andere Allergiearten und die vollständige Behandlung von Allergien sind nicht Bestandteil dieses IG.

### Artefakte

### Artefakte

Dieser Implementation Guide enthält ein FHIR-Profil und ein Beispiel zur strukturierten Dokumentation von Arzneimittelallergien.

*[DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): FHIR-Profil zur strukturierten Erfassung von Arzneimittelallergien in einer Hausarztpraxis.
*[Penicillinallergie bei Anna Muster](AllergyIntolerance-PenicillinAllergieAnnaMuster.html): Beispiel einer bestätigten Penicillinallergie mit dokumentierter Reaktion.

<!-- TODO_Name ist der Name hinter "Instance:" in beispiele.fsh,
     z. B. AllergyIntolerance-PenicillinAllergieAnna.html -->

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin oder Autor

Senn Alysha

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>
