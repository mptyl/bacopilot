A partire dallo schema Mermaid presente nel file mermaid/schema.md aggiorna le corrispondenti Entity JPA sotto la directory it.tylconsulting.nwmodel.model, creando le nuove Entity e indicando le Entity da eliminare

Se devono essere create nuove classi, crea una class per ogni entity presente dello schema, senza aggiungere nessuna Entity che non sia esplicitamente indicata nello schema Mermaid

Usa le annotazioni Lombok @Getter e @Setter, non usare l'annotazione Lombok @Data

Crea i metodi equals() e hashCode() includendo solo gli attributi che hanno la annotazione @Id

Usa le annotations jakarta per i constraints indicati nello schema

Usa il formato cameling nel naming di entità e attributi

Usa lo snake case per i nomi dei campi delle tabelle

Capitalize solo le Entità 

Usa il package jakarta al posto del package javax

Separa le classi, una classe per ogni file .java 

In risposta, indica solo le modifiche applicate alle Entity, le eventuali nuove Entity e le eventuali Entity da eliminare
