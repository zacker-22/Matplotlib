import numpy as np
import matplotlib.pyplot as plt
print ("Enter Your Attendence in each subject seperated by a space")
Atten=input().split() # Attendence Array
Nt_Deb=[]             # Array of Debarred Subjects  
Deb=[]                # Position of Debarred Subjects  
X_Nt_Deb=[]           # Array of Not Debarred Subjects                  
X_Deb=[]              # Position of Not Debarred Subjects  
for i in range(len(Atten)):
    Atten[i]=int(Atten[i])
    assert 0<=Atten[i]<=100
    if Atten[i]>=75:
        Nt_Deb.append(Atten[i])
        X_Nt_Deb.append(i)
    else:
        Deb.append(Atten[i])
        X_Deb.append(i)

plt.axis([0,len(Atten)+1,0,100])
H=["A","B","C"]
plt.bar(X_Nt_Deb,Nt_Deb,color='b',align='edge')
plt.bar(X_Deb,Deb,color='r',align='edge')
plt.show()
