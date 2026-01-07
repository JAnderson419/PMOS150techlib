# PMOS150techlib
RIT PMOS150 Technology Library for KLayout. This includes layer colors and a design rule check script to validate layouts against the rules outlined in the document published by Fuller, linked below.

https://people.rit.edu/lffeee/labnotes.htm

https://people.rit.edu/lffeee/Lec_CAD.pdf


# To Use

- Download the repository. 
- In Klayout, go to Tools > Technology Manager. In the pop up window, right click in the white Technologies list at the left and select “Import Technology.” Open the RIT_PMOS150.lyt file that is present inside the folder you downloaded.
- Restart Klayout. You should now see the PMOS process listed in your technology manager.
- To perform a design rule check, go to Tools > DRC > PMOS150 DRC. This should run the script, open the design rule check window and give you a list of any violations found in the design.
