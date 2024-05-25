# Database of TrackIt

TrackIt will use a relational database, since the type of data we plan to store is not that volatile, and the future enhancements can be modularized and migrated without consuming a great time/effort.

On this page you can check the developed diagrams and download a copy of the latest_version. To download the latest version of the diagrams:

```
Go to the project repository's url >> Access documentation folder >> assets >> database_structure
```

## DER Diagram

Track is a has a parcial specialization, the entities create from this are **Serie** and **Comic**.

This version of DER contain the following entities:

- Track: General content that the user wants to track. The required field are: id (autofilled) and name;
- Serie: Specialized type of track;
- Comic: Specialized type of track.

![DER Diagram](/documentation//assets/database_structure/track_it_der_v1.png)

## Logical Diagram

![Logical Diagram](/documentation/assets/database_structure/track_it_logico_v1.png)
