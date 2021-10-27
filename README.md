# Praktikum1
Tugas Pertemuan ke 5 Bahasa Pemograman (Python)

Langkang-langkah:
1. Download & Install Python di PC (source: python.org) & jangan lupa centang Add Python to PATH pada saat melakukan setup
2. Download & Install Sublime Text 3 di PC
3. Setelah itu masukan beberapa PATH python agar terbaca di Text Editor anda dengan cara:
Edit The Systems Environment Variable > Environment Variable > Path (Edit) > C:\Users\Imsal Yunus\AppData\Local\Programs\Python\Python310 & C:\Users\Imsal Yunus\AppData\Local\Programs\Python\Python310\Scripts > OK
4. Lakukan Instalasi beberapa Package di Sublime Text 3 anda melalui Command Palette dengan cara:
Tools > Command Palette atau Ctrl+Shift+P > ketik Install Package Control > Package Control: Install Package > SublimeREPL
Tools > Build System > New Build System > dan masukan script seperti dibawah ini:
{
  "target":"run_existing_window_command",
  "id":"repl_python_run",
  "file":"config/python/Main.sublime-menu"
}
dan simpan dengan nama Python_Run
5. Tools > Build System > Python_Run
6. Python sudah siap pakai di Text Editor Sublime Text anda (untuk melakukan nge-Build/Running/Complie pada program python anda ketik: Ctrl+B)

===============Memulai Latihan Praktikum==================
print("hello")
print("saya sedang belajar python")

a= 8
b= 6
print ("variabel a=",a)
print ("variable b=",b)
print ("hasil penjumlahan a+b=",a+b)

a=input("masukkan nilai a:")
b=input("masukkan nilai b:")
print("variabel a=",a)
print("variabel b=",b)
print("hasil penggabungan {1}&{0}=%d".format(10,5) %(10+5))

#konvensi nilai variable
a=int(a)
b=int(b)
print("hasil penjumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}/{0}=%d".format(a,b)%(a/b))



==================Membuat Tugas Program Perkenalan diri pada program Python=====================
print("=====TUGAS====")
print("=====MENGINPUT BIODATA DIRI=====")

nama =input("nama:")
call =input("panggilan:")
npm =input("npm:")
ttl =input("ttl:")
umur =input("umur:")
alamat =input("alamat:")
telepon =input("telepon:")

print("   assalamu'alaikum Wr.Wb")

print("Let me introduce my self. My Name is ",nama,", but you can call me ",call,"."
"My NPM is ",npm,". i was born in ",ttl,"and i am",umur,"years old. "
"i am very glad if you want to inivite my house in ",alamat,".so, don't forget to call me"
"before with the number",telepon,".")

print ("thank you")
