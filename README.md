https://github.com/zarodrig/HeartMuLaJupyterNotebooks.git

$ git clone https://github.com/zarodrig/HeartMuLaJupyterNotebooks.git

Purchase 100 GB of Google Drive space (Basic Plan).

https://one.google.com/plans

Log into google drive. Make a folder called HeartMuLa.  Put the two .ipynb notebooks into the folder HeartMuLa.  
Open them in Google Colab and run them cell by cell. 
Run each cell sequentially by pressing the play button arrow on the left of each cell. First open installHeartMuLa.ipynb.  
You can do this in a CPU runtime.  Then once you've run all the cells and the models are downloaded and installed, close the notebook.  

Next open runHeartMuLa.ipynb.  Switch to a GPU hosted runtime (G4, T4, A100, H100).  Then run the cells sequentially.  
It will generate a song located in HeartMuLa/heartlib/assets/output.mp3.  
You can chnage the lyrics in HeartMuLa/heartlib/assets/lyrics.txt and tags.txt , 
and change the lyrics to whatever you want and change the tags (pop, rock, 1980s, etc) to match the style of the song you intend. 
Re-run the generation cell. It will regenerate the song with the new lyrics in the new style. 

Ron Rodriguez, April 27, 2026
