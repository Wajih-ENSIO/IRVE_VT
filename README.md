1. Every combined field split apart
Parking, Énergie électrique, Bornes, and Disjoncteur général no longer have any "X / Y" fields — each part now has its own line (e.g. "Nom du parking" and "Nombre de places à équiper" are two fields; the four PDL codes are four fields, and so on).

2. "Puissance transfo (kVA)"
"tarif vert" is gone from the label, since it applies to any tariff.

3. Génie civil, now a checklist with quantities
Massifs à créer, Chambres à prévoir, Tranchées, Marquage au sol, and Protection mécanique are now pill checkboxes. Ticking one opens a small quantity box right next to it, so the tech checks "TD IRVE" and types the qty right there, instead of writing a mixed list of types and numbers in one text field. Bordure is split into "dépose" and "pose" since those aren't really the same measurement. Élagage, Percement, Carottage and Panneaux de signalisation stay as simple fields, since they were already single values.

4. Reportage photos, now one button per item
Each item (Entrée du site, Origine de l'installation, Disjoncteur général, and so on) has its own Photo and Galerie buttons and its own thumbnails. In the export ZIP, each item's photos are named after that item — for example Entree_du_site_1.jpg, Disjoncteur_general_1.jpg — instead of everything falling under one generic "Reportage" name.

A few things worth knowing:

On the Bornes section, I turned "Pose sur pied / pose murale" into two separate quantity fields, and split "Installation des bornes" so Intérieur/Extérieur stays as a simple choice (those don't need a quantity).
The PDF picks up all of this automatically: quantity checklists print as "TD IRVE (2), Borne (4)", and Reportage photos print with the item name as a small heading above its pictures.
The PowerPoint tables aren't pulling from Génie civil yet, so this change doesn't affect them. Tell me if you'd like a Génie civil summary added to a slide.
