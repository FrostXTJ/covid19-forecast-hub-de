Data about variants is extracted from the [reports published by RKI](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/DESH/Berichte-VOC-tab.html).

- Files ending in `_sample` contain counts and ratios estimated based on a random sample (usually Tables3 and 4 in the PDF files).
- Files ending `_confirmed` contain counts and ratios based on sequencing of samples with a prior suspicion of VOC ("Bestätigung durch Sequenzierung bzw. labordiagnostischer Verdacht aufgrund von variantenspezifischen PCR", usually Table 5 in the PDF files)

Note that not all historical weeks are published in the current report, we thus append to previous data. The files therefore contain the latest published values for each week.

Furthermore, RKI does not provide counts any longer, but only percentages. The counts from previous reports can be found in the `archive` folder.
