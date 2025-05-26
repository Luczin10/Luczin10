## Hi guys
<p>i am luczin, i from Brazil, São Paulo, Santana de Paraniba</p>
'''

num1= input()
num_1= int(num1)
num2=input()
num_2=int(num2)



print("Escolha uma operação:")
print("1. +")
print("2. -")
print("3. *")
print("4. /")

operacao = input("Digite o símbolo da operação (+, -, *, /): ")

if operacao == '+':
    resultado = num_1 + num_2
elif operacao == '-':
    resultado = num_1 - num_2
elif operacao == '*':
    resultado = num_1 * num_2
elif operacao == '/':
    if num2 != 0:
        resultado = num_1 / num_2
    else:
        resultado = "Erro:"
else:
    resultado = "Operação inválida"

print("Resultado:", resultado)
'''



<!--
**Luczin10/Luczin10** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
