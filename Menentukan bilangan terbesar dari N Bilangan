# Inisialisasi variabel
max_value = float('-inf')  # Set ke -∞ untuk bilangan terbesar
count = 0  # Jumlah bilangan yang diinput

print("Masukkan bilangan satu per satu. Masukkan 0 untuk berhenti.")

while True:
    try:
        # Meminta input dari pengguna
        num = float(input("Masukkan bilangan: "))
        
        # Jika input adalah 0, hentikan loop
        if num == 0:
            break
        
        # Update max_value jika num lebih besar
        if num > max_value:
            max_value = num
        
        # Tambah count
        count += 1
    except ValueError:
        print("Input tidak valid, harap masukkan angka!")

# Tampilkan hasil
if count > 0:
    print(f"\nBilangan terbesar: {max_value}")
    print(f"Jumlah bilangan yang diinput: {count}")
else:
    print("\nTidak ada bilangan yang diinput.")
