# Multimidia
Instalar o pytesseract e o python3
abrir o cmd
passar os seguintes comandos:
cd desktop
phyton3
import pytesseract
text = pytesseract.image_to_string("placa.png", lang="por")
print(text)
