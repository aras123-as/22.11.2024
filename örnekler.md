#     demet örneği 

a=(1,23,3,78)
print(a)
print(a[2])



#    sözlük örnekleri


b=("yılmaz","memet")

print(b[0])
"""
bank={
"ad"="yılmaz"
"soyad"="alaca"
"bakiye"=1000000
}

"""

api={"kullanıcıadı":"nuriil","sıfre":"654321"}

db=["nuriil","654321"]

print(api["kullanıcıadı"]==db[0])
print(api["sıfre"]==db[1])
print(api["kullanıcıadı"])




#       koşullu yapı örnekleri


yas=int(input("kütfen yaşınızı girin:"))
if (yas>18):
    print("geçebilirsiniz!!")


instagram_db={
"usarnamedb":"12345",
"sıfredb":"12345",
"date":"22.11.2024"

}
username=input("lütfen kullanıcı adını girin:")
password=input("lütfen şifrenizi girin:")
if (instagram_db["username"]==username and instagram_db["sifredb"]==password):
    print("sisteme hoşgeldin {}".format(username))



























