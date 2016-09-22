<link rel="stylesheet" type="text/css" href="css/anaesthetic_drug_colours.css">
<link rel="stylesheet" type="text/css" href="css/sticker_styling.css">

#AAGBI Drug Labelling Colours CSS Library
* This is a library of CSS classes which allow the correct AAGBI standard labelling colours to be applied to HTML elements
* It is a by product of NHS Hack Day \#13 London (May 2016), and could not have existed without the help and inspiration of others in the Anaesthesia Monitor project group, particularly Jakob Mathiszig-Lee, Fred Kingham, and David Miller.
* It is a work in progress and is incomplete. It is supplied without warranty, uner a permissive open source license (MIT), for use in development and testing of clinical user interfaces in critical care, anaesthesia, and emergency medicine.
* No responsibilty can be accepted for clinical errors relating to the use of this code in real-life environments.

#It looks like this:

<div class="drug-group">
  <div class="sticker induction_agent_drug">
    <h3>Propofol</h3>
    <h3>...................mg/ml</h3>
  </div>

  <div class="sticker induction_agent_drug">
    <h3>Ketamine</h3>
    <h3>...................mg/ml</h3>
  </div>
</div>

<div class="sticker depolarizing_neuromuscular_blocking_drug">
  <h3 class="top">Suxamethonium</h3>
  <h3>...................mg/ml</h3>
</div>

#Usage:
```html
<div class="sticker induction_agent_drug">
  <h3>Propofol</h3>
  <h3>...................mg/ml</h3>
</div>
```
is styled as:

<div class="sticker induction_agent_drug">
  <h3>Propofol</h3>
  <h3>...................mg/ml</h3>
</div>

##Notes
*
* The CSS class names have used the full text of the description of the drug class for maximum clarity, even though it makes the class names very long. If you wish to shorten or abbreviate the class names, this can of course be done, but absolute care needs to be taken that errors are not introduced in this process.
