import streamlit as st
import pyqrcode
import png

mail = st.text_input("gmail adresiniz ")
telefon = "905054407855"

# Boşlukları temizlemek için mail.replace kullandım
# Ayrıca mesaj kısmının başına '=' ekledim
link = f"https://wa.me/{telefon}?text={mail.replace(' ', '%20')}"

qr = pyqrcode.create(link)
qr.png("wp.png", scale=12)
st.image("wp.png")
