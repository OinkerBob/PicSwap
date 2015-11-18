# PicSwap Client and Supplementary Files
  This repo contains a component of a final project for the Introduction to Computer Security course at the University of Tennessee, namely, a client for a simple filesharing service that will apply AES-128 encryption in CBC mode to all files it sends. The server that is hosted on my machine will never see raw files. It will only receive and distribute the encrypted files clients running on users' machines send and the public encryption keys for the users; each user only receives public keys of their "friends"). If you're seeing this page and have access to a Hydra machine on UTK campus, you are more than welcome to download the client and test it for yourself.
  
# Dependencies
  Python 2.7 or later
  picSwap.py
  clientHelper.py
  buildDirs.py
  
  Download all three files and save them to the same directory (regardless of where you save them, PicSwap will put its 

# Please read this! :)
  This is a student project meant to highlight the encryption implementation that ought to be employed by the client of the popular image and video sharing service Snapchat. As such, my development priority is ensuring security of the temporary files stored by the client that are sent to it by other users. While the file transfer service will be functional soon, the service itself is not the focus of the project. Though it will be running on a machine in the Hydra lab, the server may be slow to respond in some cases. Experiences with the service may vary. 
  Furthermore, by using this service, you agree to refrain from using it to transfer explicit content or content that facilitates academic dishonesty. Sending or receiving any content through the client that violates this agreement will result in suspension or banning of your account. I also reserve the right to disconnect the server for any reason, be it maintenance or the distribution of files that violate the aforementioned agreement. Beyond that, maintain the same discretion that you would exhibit when using any social application; if you wouldn't staple it to a lamppost, don't send it via PicSwap. I am not responsible for any files successfully sent via the service. Keeping all that in mind, I welcome any students of the course listed above to test the client once the server is up and running!
