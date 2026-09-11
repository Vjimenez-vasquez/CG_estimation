# CG_estimation
python codes for CG% estimation and optimization

# PYTHON CODE:
```r
#!/home/vicjim/anaconda3/bin/python

def counts_seq():
    seq = input("Escribe la secuencia de ADN: ").upper()
    a = seq.count("A")
    c = seq.count("C")
    t = seq.count("T")
    g = seq.count("G")
    cg = round(((c + g) / len(seq)) * 100, 2)
    print(f"el numero de As es {a}")
    print(f"el numero de Cs es {c}")
    print(f"el numero de Ts es {t}")
    print(f"el numero de Gs es {g}")
    print(f"el numero de bases es {len(seq)}")
    print(f"el % CG es {cg}")

counts_seq()
```
