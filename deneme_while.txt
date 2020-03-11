giriş = """
toplama işlemi için (1) i
çıkarma işlemi için (2) yi tıklayanız.
"""
print(giriş)
while True:
    soru = input("yapmak istediğiniz işlemi seçiniz(çıkmak için q ya basınız.):  ")
    if soru =="q":
     print("çıkılıyir.....")
     break
    elif soru == "1" :

        sa1 = int(input("ilk sayıyı gir baba:  "))
        sa2 = int(input("ikinci sayıyı gir baba:  "))

        print(sa1,"+",sa2,"=",sa1+sa2)
        print(giriş,sep = "\n")

    elif soru == "2" :
        sa1 = int(input("ilk sayıyı gir baba:  "))
        sa2 = int(input("ikinci sayıyı gir baba:  "))
        print(sa1,"-",sa2,"=",sa1-sa2)

    else :
        print("    canım benim işlem yapmak istiyorsan ya 1 e ya 2 ye basacaksın zor değil")
        print(giriş)
 son sürüm 