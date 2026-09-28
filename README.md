# Signaling downstream of tumor-stroma interaction regulates mucinous colorectal carcinoma apicobasal polarity
__Nicolas Pasquier<sup>1,2,#</sup>, Meri Pelkonen<sup>1,#</sup>, Elise Carraz-Billat<sup>2,§</sup>, Aleksi Isomorsu<sup>1,§,\*\*</sup>, Raphaël Merand <sup>2,§</sup>,  Hellyeh Hamidi<sup>1</sup>, Jacques R.R. Mathieu<sup>2</sup>, Jouni Härkönen<sup>1</sup>, Gautier Follain<sup>1</sup>, Christophe Desterke<sup>3</sup>, Zoé Fusilier<sup>4,5</sup>, Junel Solis<sup>6</sup>, Irina Belaya<sup>6</sup>, Pasi Kankaanpää<sup>6</sup>, Valeria Barresi<sup>7</sup>, Mohammed-Amine Bani<sup>8,9</sup>, Johanna Protin<sup>2</sup>, Jérôme Cartry<sup>2</sup>, Sabrina Bedja<sup>2</sup>, Klaus Elenius<sup>1,10-12</sup>, Florent Peglion<sup>2</sup>, Fanny Jaulin<sup>*, ꟸ,2</sup> & Johanna Ivaska<sup>\*,ꟸ,1,8-11</sup>__

[See affiliations](#organizational-affiliations)

<a href="https://doi.org/10.1038/s41467-026-75127-0" target="_blank"><img alt="DOI" src="https://img.shields.io/badge/DOI-10.1038%2Fs41467--026--75127--0-blue?style=flat"></a>


## Abstract
Mucinous colorectal carcinoma (MUC CRC) metastasis to multiple organs, and to the peritoneum, is associated with poor prognosis. Disseminating MUC CRCs exhibit either conventional (apical-in) or inverted (apical-out) polarity that influence patient outcomes. Therefore, it is critical to identify how MUC CRC polarity is regulated. Here, we analyze patient-derived MUC CRC xenografts with either apical-in or apical-out polarity. Single-cell analyses reveal α2β1-integrin as a key collagen-binding receptor in these models. Collagen–α2β1-integrin interaction activates Src and upregulates SorLA, an endosomal sorting receptor. SorLA supports apical-in polarity by promoting integrin recycling and HER2/HER3 expression. We observe positive correlation between HER2, HER3 and SorLA in patient samples and higher HER2 expression in apical-in-presenting tissues. Clinically relevant HER2/HER3-targeting antibodies revert tumor sphere polarity, and impede collagen remodeling and adhesion to mouse peritoneum. This SorLA—integrin—HER2/HER3 axis could represent a MUC CRC-patient stratification approach and be relevant for other carcinomas with apical-out phenotypes.

<a href="https://doi.org/10.1038/s41467-026-75127-0" target="_blank"><img alt="Full Text - Nature Communications" src="https://img.shields.io/badge/Full_Text-Nature_Communications-blue?style=flat"></a>


## Image data
[Update with links to Fairdata.fi]

## Image processing workflow
This repository contains the image processing code used in the manuscript. Download the required image data and metadata (see Image data section).

- [ ] Clone this repository
- [ ] Configure a Python environment using `environment.yml`
- [ ] Run `./util/convert_to_zarr.py` to generate a Zarr dataset of all the input images.
- [ ] Run `./main.py`

## Organizational affiliations
<sup>1</sup>Turku Bioscience Centre, University of Turku and Åbo Akademi University, Turku, Finland  
<sup>2</sup>Université Paris-Saclay, Gustave Roussy, Inserm, UMR 1279 Tumor Cell Dynamics, F-94805, Villejuif, France  
<sup>3</sup>INSERM UMR-S1310, Université Paris-Saclay, Hôpital Paul Brousse, Villejuif F-94805, France  
<sup>4</sup>INSERM-U932, Immunity and Cancer, Institut Curie, Paris-Cité University, Paris, France  
<sup>5</sup>INSERM-U932, Immunity and Cancer, Institut Curie, PSL University, Paris, France  
<sup>6</sup>Turku BioImaging, Åbo Akademi University and University of Turku, Turku, Finland  
<sup>7</sup>Department of Diagnostics and Public Health, University of Verona, Verona 37134, Italy  
<sup>8</sup>Medical Biology and Pathology Department, Pathology Laboratory, Gustave Roussy Cancer Campus, Villejuif, France  
<sup>9</sup>Platform for Experimental and Translational Pathology (PETRA), Gustave Roussy Cancer Campus, Villejuif, France  
<sup>10</sup>Institute of Biomedicine, and MediCity Research Laboratory, University of Turku, Turku, Finland  
<sup>11</sup>Department of Oncology, Turku University Hospital, Turku, Finland  
<sup>12</sup>InFLAMES Research Flagship Center, University of Turku, Turku, Finland  
<sup>13</sup>Department of Life Technologies, University of Turku, Turku, Finland  
<sup>14</sup>Foundation for the Finnish Cancer Institute, Helsinki, Finland  
<sup>15</sup>Western Finnish Cancer Center, University of Turku, Turku FI-20520, Finland    

<sup>#</sup>Equal contribution  
<sup>§</sup>Equal contribution  
<sup>ꟸ </sup>Equal contribution  
<sup>*</sup>Correspondence: johanna.ivaska@utu.fi and fanny.jaulin@gustaveroussy.fr  
<sup>**</sup>Current address: Cell Polarity, Migration and Cancer Unit, Institut Pasteur, CNRS UMR3691, Université Paris
Cité, Équipe Labellisée Ligue Contre le Cancer, F-75015, Paris, France  
