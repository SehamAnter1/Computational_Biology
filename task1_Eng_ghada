from pyopenms import *
sq="VAKA"
mfull2=0
for i in range(0,len(sq)):
    q=sq[i]
    e = AASequence.fromString(q)
    mfull2=mfull2+e.getMonoWeight()
    print(mfull2)
seq = AASequence.fromString(sq)
print("Sequence:", seq)

mfull = seq.getMonoWeight()

print("Monoisotopic mass of peptide [M] is", mfull)
