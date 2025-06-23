# EBAC
## Pre processamento de dados - Etapa 1 --> Pre modelagem

Uma empresa de telecomunicacao forneceu uma base de churn para nos retirarmos insights importantes e fazer o tratamento do data frame.

Primeiro passo e a importacao das bibliotecas necessarias e visualizacao do nosso data frame.
![image](https://github.com/user-attachments/assets/6dc18551-3678-42d4-acfc-040d4e53cb8b)

Apos isso analizamos os tipos de dados que cada coluna oferece para facilitar nossa analise, e caso nao satisfaca iremos fazer trasformacao dos dados.
![image](https://github.com/user-attachments/assets/c2e249be-1b05-4dd9-a9b3-2d9f072deda2)

As colunas 'Idoso', 'Casado', 'Dependents' e 'Churn' estavam como object, fizemos a mudanca neles para facilitar o plotagem de graficos e calculos matematicos, sao valores boleanos que podem influenciar em nossa analise. 
![image](https://github.com/user-attachments/assets/3a3e5278-69d9-4d21-af44-928e64748a10)

Em seguida aferimos os valores nulos e como iremos lidar com ele.
![image](https://github.com/user-attachments/assets/ec7ff605-f7cf-4c66-a5a2-ad88f57bee7e)

Por se tratar de um valor muito alto, que nao consegue oferecer media e que pouco agrega na nossa analise, decedi apagar a coluna 'PhoneService'.
![image](https://github.com/user-attachments/assets/2215ee23-6819-4c06-b3b3-6ae9c0f89641)

Ja a coluna 'Pagamento_Mensal' e de alto valor e podemos calcluar a media, por isso fizemos o preenchimento pela media.
![image](https://github.com/user-attachments/assets/8334309b-01f5-476b-9e18-a00af2e04887)

Por fim, a coluna genero teve apenas 12 linhas de valores nulos, valor infimo quando comparado ao nosso dataframe, por isso optei por excluir.
![image](https://github.com/user-attachments/assets/4533e51b-3585-4ced-a089-8d93c048f2a8)

Agora, para finalizar, padronizei a coluna genero.
![image](https://github.com/user-attachments/assets/6940c076-90cb-4f97-ae82-d8728174a9b9)

