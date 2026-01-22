# Common metadata format/specification for every library
# library_prep - (Required) str
# Donor ID - (Required) str
# Brain Region - (Reguired) literal Any feature in the Allen Brain Atlas: https://atlas.brain-map.org/atlas?atlas=138322605
# Method - (Required) literal "3' 10x v2", "3' 10x v3", "3' 10x v3.1", "3' 10x v4", "3' 10x Multiome v1", "3' 10x Multiome v2", "5' 10x v1", "Microwell-Seq", or "Seqwell"
# RIN - float
# barcode - str
# HTO - str
# Treatment - str

# Common metadata format/specification for every donor
# Donor ID - (Required) str
# Primary Study Name - (Required) str
# Age at Death - int, float or literal '90+'
# Sex - literal, "Male" or "Female"
# Race (choice=White) - literal "Checked" or "Unchecked"
# Race (choice=Black/ African American) - literal "Checked" or "Unchecked"
# Race (choice=Asian) - literal "Checked" or "Unchecked"
# Race (choice=American Indian/ Alaska Native) - literal "Checked" or "Unchecked"
# Race (choice=Native Hawaiian or Pacific Islander) - literal "Checked" or "Unchecked"
# Race (choice=Unknown or unreported) - literal "Checked" or "Unchecked"
# Race (choice=Other) - literal "Checked" or "Unchecked"
# Hispanic/Latino - literal "Yes" or "No"
# Years of education - int or float
# APOE4 Status - literal 'Yes' or 'No'
# PMI - float
# Fresh Brain Weight - float
# Brain pH - float
# Overall AD neuropathological Change - literal "Not AD", "Low", "Intermediate", or "High"
# Thal - literal "Thal 0", "Thal 1", "Thal 2", "Thal 3", "Thal 4", or "Thal 5"
# Braak - literal "Braak 0", "Braak I", "Braak II", "Braak III", "Braak IV", "Braak V", or "Braak VI"
# CERAD score - literal 'Absent', 'Sparse', 'Moderate', or 'Frequent'
# Cognitive Status - literal 'No dementia' or 'Dementia'
# Highest Lewy Body Disease - literal 'Not Identified (olfactory bulb not assessed)', 'Not Identified (olfactory bulb assessed)', 'Olfactory bulb only', 'Amygdala-predominant', 'Brainstem-predominant', 'Limbic (Transitional)', or 'Neocortical (Diffuse)'
# LATE - literal 'Unclassifiable', 'Not Identified', 'LATE Stage 1', 'LATE Stage 2', 'LATE Stage 3'
# Overall CAA Score - literal 'Not identified', 'Mild', 'Moderate', 'Severe'
# Atherosclerosis - literal 'None', 'Mild', 'Moderate', 'Severe'
# Arteriolosclerosis - literal 'None', 'Mild', 'Moderate', 'Severe'
