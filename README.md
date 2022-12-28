# praktikum_12

# Latihan string python
txt = 'Hello World'
- hitung jumlah karakternya
- ambil karakter terakhir
- ambil karakter index ke-2 sampai index ke-4(llo)
- hilangkan spasi pada text tersebut(HelloWorld)
- ubah text menjadi huruf besar
- ubah text menjadi huruf kecil
- ganti karakter H menjadi karakter J

# Program
txt = 'Hello World'

# Hitung jumlah karakternya
print(len(txt)) #Output:

# Ambil karakter terakhir
print(txt[-1]) # Output: d

# Ambil karakter index ke-2 sampai index ke-4 (llo)
print(txt[2:5])  # Output: llo

# Hilangkan spasi pada text tersebut (HelloWorld)
txt = txt.replace(' ', '')
print(txt)  # Output: HelloWorld

# Ubah text menjadi huruf besar
print(txt.upper())  # Output: HELLOWORLD

# Ubah text menjadi huruf kecil
print(txt.lower())  # Output: helloworld

# Ganti karakter H dengan karakter J
print(txt.replace('H', 'J'))  # Output:JelloWorld