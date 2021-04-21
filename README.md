# Capstone
### Transformers in the field of Audio Classification: Speaker recognition
A PESU final year project by Aayush Shah, Kayan Katrak, Kanish Singh and Rohit Menon.

## Capstone Repository for VRB01

All files are executable using Google Collab. There is no need to externally download dependencies as the notebook will dynamically take care of all the requirements.
In case the code base needs to be tested externally [specification file](spec-file.txt) can be used to download dependencies for any environment.
 In such cases, if certain dependencies need to be redownloaded add a code block at the end of the required file and use command `!pip list -v`
 
 ## Executables
- For testing the tranformer on a public dataset, use the [librispeech transformer file](Tranformer_librispeech.ipynb)
- For testing the transformer on a private dataset, use the [custom dataset tranformer file](Tranformer_ourdataset.ipynb)
- To view how we take care of interfacing the dataset with networks, use the repective [public](Datasethandling_librispeech.ipynb) and [custom](Datasethandling_ourspeech.ipynb) files
- You can also view how we take [input](VoiceInput.ipynb) an [reduce noise](noisereduce.ipynb) from these files.

## Database warning
While running notebooks from this repo, you will have to give access to you google drive account. Note, that if you want to view preliminary results,you may have to request access from the drive owner.

For further enquiries, contact Aayush,Kayan,Kanishk and Rohit at dr3amt3am007@gmail.com

 
