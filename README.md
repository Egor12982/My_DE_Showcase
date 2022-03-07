# My_DE_Showcase
This case for some examples of my DE works and materials studied

!!!IMPORTANT INFORMATION!!!
There are two different versions in this branch: FOR WINDOWS and FOR UBUNTU-WINDOWS.
Automatical version is FOR UBUNTU-WINDOWS, it's the original one and marked like
"Spotify_Data_Extraction". I think, that this version can work, with some corrections, on Ubuntu only,
cause Windows in a bundle "UBUNTU-WINDOWS" only because I don't have clear Linux PC. 

If your have situation like me, you need to install on your Windows Ubuntu with Apache Airflow to be installed and paths set up.
I will add instructions about installation later, but you can find it by yourself in Google, you can find virtual Ubuntu here: www.microsoft.com 
After that you need to download the "Dag_for_Spotify_Data_Extraction" file and put it to your DAG directory. 
Next step is to run in Ubuntu terminal "airflow webserver" and "airflow scheduler", also you can run your visual interface in the browser,
just write in the address bar: "localhost:8080". 
First preparation done, but you need to fill the code with your Sporify ID and refresh token if you want automatical work without refreshing
your token every our by hands.
That's all, new information will be added every day, if you have listened something the day before.

Windows version, marked like "Spotify_Data_Extraction_for_Windows" is non fully automatical, you need manually run the code and refresh your 
token by hands, before running. Cons of that version is that you need only Windows and your IDE, information will be saved on your desk in
NoSQL format. 

Problems with Windows version:
1. Code doesn't work ---> You need to run your IDE with administrator rights.
2. Attribute error ---> Your token is too old, refresh it and try again.
