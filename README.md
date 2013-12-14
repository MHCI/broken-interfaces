# Broken Interface Dataset

The broken interface dataset contains images of broken smartphone displays, visual damage annotations, and additional survey data collected in 2013 through an online survey. This dataset is supplemental material to our CHI'14 paper "Broken Display = Broken Interface? The Impact of Display Damage on Smartphone Interaction." 

## License
The broken interface dataset is licensed under the *Creative Commons Attribution 4.0 International License*. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/

You are free to use this dataset for your own research. Please attribute us when you use the dataset by citing our paper:

Florian Schaub, Julian Seifert, Frank Honold, Michael Müller, Enrico Rukzio, Michael Weber, "Broken Display = Broken Interface? The Impact of Display Damage on Smartphone Interaction", CHI'14: Proceedings of the 2014 CHI Conference on Human Factors in Computing Systems, ACM, 2014. http://dx.doi.org/10.1145/2556288.2557067 

If you want to provide a link to the dataset, please use the following URL:

http://www.uni-ulm.de/broken-interfaces


## Structure
This dataset is organized in the following way: 

### Online survey data
* `Survey_Questionnaire.xlsx`: participant responses provided alongside the damage photos.

### Photo data
* `phone_originals/`: contains the original photos uploaded by participants (*.jpg, *.png).
* `phone_cropped_display/`: contains only the display area of the photos (*.png).
* `phone_damage_annotation/`: contains SVGs with manually annotated damages.
* `phone_damage_overlay/`: contains PNG overlays: damage + display photos.