# Malware GDI in C#  

## 📜 Introduction  
This is an old GDI malware I made in C#, and now I’m making it public.  
The malware was originally created for **nFire**, an Italian cybersecurity YouTube channel.  
It consists of a part written in **C#** and the **MBR** written in Assembly.  

---

## 🛠️ Main Features  
- **OS Detection**: Dosen't support windows 10 or 11  
- **GDI (Effects)**: LSD TRIP
- **Bytebeat**: randomly generated sounds.  
- **Partial Destruction**: attempts to damage **Regedit** and **System32** (although this does not work properly) and ovewrite the mbr
- **Multiple MBRs**: in the version with 4 MBRs, the malware uses random to decide which of the 4 MBRs to execute.  

---

## 🔄 Differences from the Version on my yt channel?
### Main Changes:  
1. **Duration**:  
   - The duration of the original version was 10 minutes, but it was boring.  
   - Now, there are two versions with different durations:  
     - **Version with 4 MBRs**: shorter than the original version but with 4 random mbr.  
     - **Version with 1 MBR**: shorter, but retains the same payloads.   

## ⚠️ Disclaimer  
This project is published **for educational purposes only**. 
