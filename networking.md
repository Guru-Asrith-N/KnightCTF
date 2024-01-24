# networking

### vicker IP

opened the challenge   
opened the attachment  
couldn't open in google drive  
downloaded it  
read the challenge and realised it was a packet capture type of challenge   
opened the file in wireshark    
started searching for all http sites since they are generally the vulnerable ones as https ones are secure   
added filters of http   
started searching manually and couldn't find it  
found that you can sort all packets using 'Export objects' in file   
clicked on 'file' , clicked on 'Export objects' and entered http files   
started searching through each content type individually   
found a suspicious filename in application/x-zip-compressed named maybeconfidential.zip     
tried tracing it and found source and destination   
read the challenge and realised that the person who initiated the http file transfer is the attacker   
entered the ip address but it was wrong   
