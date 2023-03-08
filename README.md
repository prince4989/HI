# NBME--clinical-patient-notes
A patient note is the primary communication tool to other clinicians treating the patient, and a statement of the quality of care. EHRs aim to assist you in writing a patient note, but in the end, the note comes from you, the physician or caregiver, not from the EHR.
PREPROCESSING
Cleaning text with regular expressions
• Generalizing Case, where we convert all letters to lower case
• Ignoring Punctuation, we can do this by keeping everything in the 
text that does not belong to string. punctuation (a pre initialized 
string that contains all sets of punctuations)
• Ignoring stop words that don’t provide any information. Here we 
import a list of most frequently used words from the nltk.corpus and 
remove them as they reduce the predictive power of the model.
Tokenization
• Tokenization is splitting a phrase, sentence, paragraph, or an entire 
text document into smaller units such as individual words or terms
