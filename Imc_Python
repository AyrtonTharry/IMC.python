from tkinter import *
from tkinter import ttk

janela = Tk()
janela.title("Calculadora de IMC")
janela.geometry("295x230")
janela.configure(bg="#feffff")

frame_cima = Frame(janela, width=295, height=50, bg="#feffff", relief="flat")
frame_cima.grid(row=0, column=0, sticky=NSEW)

frame_baixo = Frame(janela, width=295, height=200, bg="#feffff", relief="flat")
frame_baixo.grid(row=1, column=0, sticky=NSEW)

app_nome = Label(frame_cima, text="Calculadora de IMC", width=23, 
height=1, padx=0, relief="flat", anchor="center",
font=("Ivy 16 bold"), bg="#feffff", fg="#444466")
app_nome.place(x=0, y=2)

l_peso = Label(frame_baixo, text="Insira seu peso", 
height=1, padx=0, relief="flat", anchor="center", 
font=("Ivy 10 bold"), bg="#feffff", fg="#444466")
l_peso.place(x=0, y=10)

entrada_peso = Entry(frame_baixo)
entrada_peso.place(x=0, y=30)

def calcular_imc():
    peso = float(entrada_peso.get())
    altura = float(entrada_altura.get())
    imc = peso / (altura ** 2)
    # Aqui você pode adicionar a lógica para classificar o IMC em categorias 
    #(abaixo do peso, normal, sobrepeso, obesidade)
    # e exibir o resultado na interface gráfica.

botao_calcular = Button(frame_baixo, text="Calcular", command=calcular_imc)
botao_calcular.place(x=0, y=60)

janela.mainloop()

