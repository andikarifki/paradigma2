# ANDIKA RIFQI ISTANTO
# 163210002/KOMPUTERISASI AKUNTANSI 
# NO ABSEN : 01

```python
def pin():  
    tries = 3
    while tries >=0:
        pin = int(input('Silahkan Masukkan Pin Anda : '))
        if pin==(5000):
            print("Pin Benar, Silahkan Pilih Transaksi")
            return True
        else:
            print("Pin Salah, Silahkan Masukkan Pin Kembali")
            tries += 1
    print("Pin Salah, Kartu Terblokir")
    return False
def menu():
    balance=1000000
   
    print('Terimakasih Sudah Melakukan Transaksi Di Mesin ATM .')
  
    if pin():
            print('1 Melihat Saldo\n')
            print('2 Penarikan\n')
            print('3 Penyetoran\n')
            print('4 Keluar\n')

            transaction = int(input('Pilih Transaksi yang Akan Anda Lakukan Hari ini :'))
            if transaction == 1:
                print('Saldo Anda Adalah : Rp ',balance)
                restart = input('Apakah Anda Akan Melakukan Transaksi Lagi ? ')
                if restart in ('NO','no'):
                    print('Terimakasih telah melakukan transaksi di ATM kami type menu()')
                 
            elif transaction == 2:
                
                withdrawl = float(input('Masukkan Jumlah Penarikan : '))
                if withdrawl in []:
                    balance = balance - withdrawl
                    print ('Jumlah Saldo Anda Sekarang : Rp ',balance)
                    restart = input('Apakah Anda Akan Melakukan Transaksi Lagi ? ')
                    if restart in ('NO','no'):
                        print('Terimakasih telah melakukan transaksi di  ATM-AWOKOWAWO Kami type menu()')
                    
                elif withdrawl != []:
                    print('Saldo Tidak Cukup\n')
                    restart = ('yes')
                
            elif transaction == 3:
                deposit = float(input('Berapa Banyak Uang Yang Akan Didepositt  '))
                balance = balance + deposit
                print('Jumlah Uang',balance,'\n')
                restart = input('Apakah Anda Akan Melakukan Transaksi Lagi ?  ')
                if restart in ('NO','no'):
                    print('TTerimakasih telah melakukan transaksi di ATM type menu() ')
               
            elif transaction == 4:
                
                print('Terimakasih telah melakukan transaksi di  ATM-AWOKOWAWO Kami type menu()\n')
                print("Exiting Program, type start_menu() ")

menu()def pin():  
    tries = 3
    while tries >=0:
        pin = int(input('Silahkan Masukkan Pin Anda : '))
        if pin==(5000):
            print("Pin Benar, Silahkan Pilih Transaksi")
            return True
        else:
            print("Pin Salah, Silahkan Masukkan Pin Kembali")
            tries += 1
    print("Pin Salah, Kartu Terblokir")
    return False
def menu():
    balance=1000000
   
    print('Terimakasih Sudah Melakukan Transaksi Di Mesin ATM .')
  
    if pin():
            print('1 Melihat Saldo\n')
            print('2 Penarikan\n')
            print('3 Penyetoran\n')
            print('4 Keluar\n')

            transaction = int(input('Pilih Transaksi yang Akan Anda Lakukan Hari ini :'))
            if transaction == 1:
                print('Saldo Anda Adalah : Rp ',balance)
                restart = input('Apakah Anda Akan Melakukan Transaksi Lagi ? ')
                if restart in ('NO','no'):
                    print('Terimakasih telah melakukan transaksi di ATM kami type menu()')
                 
            elif transaction == 2:
                
                withdrawl = float(input('Masukkan Jumlah Penarikan : '))
                if withdrawl in []:
                    balance = balance - withdrawl
                    print ('Jumlah Saldo Anda Sekarang : Rp ',balance)
                    restart = input('Apakah Anda Akan Melakukan Transaksi Lagi ? ')
                    if restart in ('NO','no'):
                        print('Terimakasih telah melakukan transaksi di  ATM-AWOKOWAWO Kami type menu()')
                    
                elif withdrawl != []:
                    print('Saldo Tidak Cukup\n')
                    restart = ('yes')
                
            elif transaction == 3:
                deposit = float(input('Berapa Banyak Uang Yang Akan Didepositt  '))
                balance = balance + deposit
                print('Jumlah Uang',balance,'\n')
                restart = input('Apakah Anda Akan Melakukan Transaksi Lagi ?  ')
                if restart in ('NO','no'):
                    print('TTerimakasih telah melakukan transaksi di ATM type menu() ')
               
            elif transaction == 4:
                
                print('Terimakasih telah melakukan transaksi di  ATM-AWOKOWAWO Kami type menu()\n')
                print("Exiting Program, type start_menu() ")

menu()
```

