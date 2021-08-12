# PequenaAutoma-oComPython
Atomação para abrir novas guias fazer pesquisas na internet de forma autonoma apenas execultando o codigo.
Estou usando a IDE Jupyter mas ja testei no Pycharm e funcionou mas em outras IDEs não execultei o teste.
Primeiro é necessario baixar as bilbiotecas 

"import pyautogui"
"import time"
"import pyperclip"

Após a instalação execulte o ultimo codigo.
time.sleep(4)
print(pyautogui.position())
pyautogui.alert("Posição Registrada")

Para registrar a posição do seu Mouse no seu computador pois as posições de pixel dos monitores são diferentes,
após isso basta substituir as mesmas no codigo principal para ver a mágica acontecer.
