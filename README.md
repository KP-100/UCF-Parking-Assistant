# UCF-Parking-Assistant Prototype
Prototype web application that provides parking garage availability for University of Central Florida

# Executive Summary
- UCF commuters face an unpredictable and frustrating parking experience: students routinely drive
between multiple garages before finding an open space, and the tools available to them (Google Maps and
the official UCF parking website) are fragmented and disconnected from one another. No single source
combines live availability with navigation, and a prior official parking app was frustrating enough that at
least one participant in our research abandoned it entirely.

- Our team designed the UCF Campus Parking Assistant, a mobile-first web app that overlays real-time,
color-coded garage availability on a familiar map interface. Core features include navigation to a selected
garage, quick links to permits, and citation resources and favorited garages with availability notifications.

- User research with five UCF commuters confirmed that availability unpredictability and tool
disjointedness were the primary pain points. Students preferred a simple, color-coded map over a feature-
dense interface. These insights were translated into five functional requirements (FR1-FR5) covering real-
time availability, event/closure alerts, quick links, favorites/notifications, and navigation.

- A four-participant usability evaluation tested the resulting high-fidelity prototype against two of these fit
criteria. The navigation feature (FR5) passed convincingly, with an average launch time of 5.0 seconds
and zero errors confirms that removing manual address entry meaningfully streamlines the commute-to-
parking workflow. However, the live data refresh mechanism (NFR3) failed from a UX standpoint:
although the backend returned data quickly once triggered, a refresh button was difficult for participants
to locate, driving average interaction time to 13.5 seconds and producing the evaluation's highest error
counts. A second recurring issue was the map's reliance on garage letters rather than familiar campus
landmarks, which increased cognitive load for participants navigating by mental images of campus rather
than a lettering system.

- Taken together, these findings show a prototype with a genuinely successful core interaction (navigation)
undermined by a discoverability failure in a supporting feature (refresh) and a mapping mismatch
between the system's internal vocabulary (garage letters) and users' mental models (campus landmarks).
Section 3 details these findings against the project's Fit Criteria, and Section 5 outlines the three design
changes we would prioritize first if development continued.

# Prototype Images
- This image provides our first sketches and drafts. Overtime improving until a final prototype sketch was achieved.
<img width="1440" height="686" alt="image" src="https://github.com/user-attachments/assets/0d082ab7-9a28-47cd-8725-83c1942dc441" />
<br>
<br>
<br>
<br>
<br>


- This image shows out final UI of all the garages and the UCF theme overlay.
<img width="515" height="759" alt="image" src="https://github.com/user-attachments/assets/156c69fa-03ca-4ebe-b125-627fd1bb57f2" />
<br>
<br>
<br>
<br>
<br>

- This image shows a close up view of the garage UI when selected.
<img width="479" height="284" alt="image" src="https://github.com/user-attachments/assets/db3e43c4-e45f-499a-aa79-42c6409f8205" />
<br>
<br>
<br>
<br>
<br>
<br>

- This image shows the quick links UI that leads to their respective pages on the official UCF website
<img width="512" height="633" alt="image" src="https://github.com/user-attachments/assets/b59440be-cf55-45c2-9c03-b461b8e493fa" />
<br>
<br>
<br>
<br>
<br>
<br>

- This image shows the overall UI view of parking garage.
<img width="542" height="760" alt="image" src="https://github.com/user-attachments/assets/3eae0eb2-858d-4feb-80c5-73c6a4aafbc4" />

<br>
<br>
<br>

# Prototype Live Demo
- Disclaimer: This application is an unofficial, group student project for "foundations of HCI" and is not affiliated with, endorsed by, or maintained by the University of Central Florida (UCF). UCF does not provide a public parking API; this application functions solely as a prototype/demo using simulated or publicly available data layout. Use at your own risk.
- [Click Here](https://vowel-eagle-08927390.figma.site/)
