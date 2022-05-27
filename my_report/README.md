# Lesson: Interaction Design

### First and Last Name: Paraskevi Xenoktistaki 
### University Registration Number: dpsd19143
### GitHub Personal Profile: EvitaXen 
### Augmented Reality Personal Repository: xxx

# Introduction

# Summary


# 1st Deliverable

Πρώτα δημιούργησα έναν λογαριασμό Github, έκανα fork το repository και μετά κατέβασα το Github στο Desktop. Έκανα λήψη των αρχείων στον υπολογιστή μου και έπειτα του Αtom. Και ρύθμισα τον τοπικό διακομιστή python 3. Τα σχήματα κύλινδρο και σφαίρα τα βρήκα από το A-frame και έπειτα επεξεργάστηκα τον κώδικα να τα εμφανίζει όταν η κάμερα αναγνωρίζει το hiro, και μετά επεξεργάστηκα το position τα χρώματα και τα μεγέθη και των τριών. Μετά έβαλα την εντολή για να χιονίζει από το Α-Frame particle system component και από το Α-Frame speech command component πήρα την εντολη annyang-speech-recognition και επεξεργάστηκα τις δύο τελευταίες εντολές άλλαξα το id, το command για τα δέχεται τις έντολες start stop και πρόσθεσα το targetElement για να εκτελείται η εντολή στο χιόνι.

# 2nd Deliverable

- Πρώτα έψαξα για τους [custom markers](https://www.oodlestechnologies.com/blogs/how-to-create-your-own-marker-for-ar-js/), και προσπάθησα να φτιάξω το **Dpsd pattern** με το [text](https://www.oodlestechnologies.com/blogs/how-to-create-your-own-marker-for-ar-js/), την [εικόνα](https://aframe.io/docs/1.3.0/primitives/a-image.html), και τα έκανα να είναι παράλληλα με την οθόνη, [με αυτή την εντολή](https://aframe.io/docs/1.3.0/primitives/a-plane.html) "rotation="-90 0 0".

![image](https://user-images.githubusercontent.com/101424559/168429705-9d94b501-5403-4cce-a1ee-f841f875bb1c.png)

- Στην συνέχεια κατέβασα το Βlender, έπειτα έκανα το **οξυγόνο και υδρογόνο** με αυτό το [tutorial](https://www.youtube.com/watch?v=hGdU3GgbTMY). Ενώ το **νερό** προσπάθησα να το φτιάξω από [εδώ](https://www.youtube.com/watch?v=8wB265I_MH0). 
###### Με την σειρά, το υδρογόνο, το οξυγόνο και το νερό. 
<img src="https://user-images.githubusercontent.com/101424559/168422982-f36a0fbc-7c9f-4e34-acd7-d9f80efad06a.png" width="180" height="160">
<img src="https://user-images.githubusercontent.com/101424559/168423006-a7ea0890-73f2-41fd-9242-f75c5e5755aa.png" width="180" height="160">
<img src="https://user-images.githubusercontent.com/101424559/168422765-91eed3da-8bda-4d14-a38b-10b0fa61f43e.png" width="300" height="160">

- Από αυτό το [βίντεο](https://www.youtube.com/watch?v=YSzbIWo1UWk), είδα πως να κάνω export τα αρχεία το οποία ήταν εν τέλη λάθος γιατί ηταν .glb και χρειάστηκε να τα κάνω import στο Βlender και μετά ξανά export σε gltf. 
- Αφότου έφτιαξα και τα patterns του υδρογόνου και του οξυγόνου. Για να βάλω τα animation να εμφανίζονται από τους custom markers χρησιμοποίησα τον κώδικα που βρήκα μέσω [A-frame](https://aframe.io/blog/arjs/)
- **Για το τρίτο βήμα**. Πήρα τον κώδικα για την [απόσταση των δύο markers](https://stackoverflow.com/questions/61239107/how-to-get-marker-position-x-y-ar-js). Βρήκα από το [Α-frame](https://aframe.io/docs/1.3.0/core/entity.html#properties) και από [εδώ](https://stackoverflow.com/questions/67578125/a-frame-show-gltf-model-if-variable-has-a-certain-value), πως να "καλώ" τις entities και να διαχειριστώ το "visibility". Και τέλος τοποθέτησα το script, [με αυτές τις οδηγίες](https://aframe.io/docs/0.8.0/introduction/writing-a-component.html), εν τέλη δεν δούλεψε αλλά δεν βρήκα το γιατί.

# 3nd Deliverable

- Πρώτα, έψαξα και κατέβασα τον πύργο του Άιφελ σε .gltf αρχείο από αυτό το [site](https://sketchfab.com/tags/eiffeltower). Και βρήκα τις γεωγραφικές συντεταγμένες της Γαλλίας απ'το Google.
<img src="https://user-images.githubusercontent.com/101424559/170276776-e293fc52-a5cc-4737-bc2d-74f8d5be790f.png" width="340" height="100">

- Στην συνέχεια, τις εισήγαγα στο gps-entity-place που βρήκα μέσω [A-frame](https://aframe.io/blog/arjs3/). Μέσα στο entity που περιέχει το .gltf μοντέλο και άλλαξα και τις συντεταγμένες στο gps-camera ώστε να εμφανίζεται το animation.

![image](https://user-images.githubusercontent.com/101424559/170736172-73a4fc02-e99c-41cb-92db-97d311b835a1.png)
![image](https://user-images.githubusercontent.com/101424559/170736101-f9013ceb-88a4-4a3f-9f88-f299c6e518fb.png)

- Έπειτα, τροποποιήσα τον κώδικα μου με την βοήθεια [αυτόυ του παραδείγματος](https://glitch.com/~salty-partner-1), ώστε όταν κάνετε κλικ στο animation, να εμφανίζεται το [text](https://aframe.io/docs/1.3.0/components/text.html#fonts2_kelsonsans).

<img src= "https://user-images.githubusercontent.com/101424559/170280485-381b5845-d1a2-4a7f-b6ee-115644654fc0.png" width="250" height="250">

- Για το τρίτο βήμα, κατέβασα μία φωτογραφία από [εδώ](https://www.greecevacationsearch.com/el/%CF%80%CE%B1%CF%81%CE%B1%CE%BB%CE%B9%CE%B1/%CE%9A%CF%8C%CE%BA%CE%BA%CE%B9%CE%BD%CE%B1/%CE%A3%CF%8D%CF%81%CE%BF%CF%82) με την παραλία Κόκκινα. Έβαλα την εικόνα σε [plane](https://aframe.io/docs/1.3.0/primitives/a-plane.html) για να την προσαρμόσω στο scene. Ενώ από το Google maps βρήκα τις συντεταγμένες.

![image](https://user-images.githubusercontent.com/101424559/170315984-c1516b88-055b-431f-816d-b412efab126b.png)

# Conclusions


# Sources
