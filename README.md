# AI_Detection_EEG

## Abstract:

Electroencephalogram (EEG) brain waves are an extremely important resource for clinical analysis and diagnosis of mental health and other psychiatric diseases. They help current diagnosis of these diseases, as clinics use the external behavior of a patient and the psychiatrist’s qualitative reasoning to determine what disease the patient has. However, this approach does not examine internal activity in the brain, and is not uniformly quantifiable. EEG provides a means for psychiatrists to do this, however, this process can be complicated because the variability in EEG signals. Machine Learning (ML) provides a means to analyze these complex data. A computational tool that can recognize patterns in EEG signals would be a valuable starting point in diagnosis psychiatric disorders. We proceeded to develop a recurrent neural network (RNN) model structure that could analyze an individual’s brain waves and predict their emotional condition. We used the EEG Brainwave Dataset: Feeling Emotions dataset, which contains various statistical features of the EEG brain waves of two different test subjects as they were experiencing different emotions. We extracted frequency domain features, converted them to the time domain, and filtered them. We trained a gated recurrent unit (GRU) model from these filtered and attained a 96.95% validation accuracy.

Link to research paper: https://figshare.com/articles/journal_contribution/Srinivas_Sriram_Research_paper_pdf/21947732/1
