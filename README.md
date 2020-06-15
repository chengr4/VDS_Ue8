Die enthaltenen Skripte erzeugen und befüllen (填充) das Schema SRDemo (siehe SRDEMO.pdf).

* 01_createUser.sql: erzeugt Nutzer und setzt Berechtigungen 創建用戶並設置權限
* 02_createSchemaObjects.sql: erzeugt Tabellen, Indizes und Sequenzen
* 03_createSequenceTriggers.sql: erzeugt Sequenz-Trigger (optional)
* 04_populateSchemaTables.sql: befüllt die Tabellen mit Daten (INSERTs)
* *.csv: enthalten generierte Daten im CSV-Format.  
  Die Datumswerte sind etwas älter. Spalten mit TIMESTAMP-Typ sind in den CSV-Daten nur als Datumswert hinterlegt.  
  Beides ist für den zu betrachtenden Anwendungsfall nebensächlich (次要).????
* SRDEMO.pdf: enthält die Beschreibung der Tabellen des Schemas

---
Letzte Änderung: 27.05.2020


# VDS_Ue8
