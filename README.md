### author-id-project
Author Identification using Deep Learning Project

For Text_Pre_Processing, you need to download Stanford NER from here: https://nlp.stanford.edu/software/CRF-NER.shtml#Download
Place the stanford-ner.jar and english.all.3class.distsim.crf.ser.gz files in the same directory as your code. They are called in the code as:  

jar = './stanford-ner.jar'
model = './english.all.3class.distsim.crf.ser.gz'

If they are not in the correct directory, java will throw a "Java command failed" error.
