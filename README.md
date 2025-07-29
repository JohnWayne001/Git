# Git
## Entre no terminal e configure seu nome e e-mail
<img width="703" height="166" alt="image" src="https://github.com/user-attachments/assets/4a657474-1689-4d88-b0f5-18b0e8ceb263" />

### Para configurar coloque os seguintes códigos:
#### git config --global user.name "Seu nome"
#### git config --global user.e-mail "Seu e-mail"
## Após isso verifique suas configurações
<img width="616" height="394" alt="image" src="https://github.com/user-attachments/assets/e6195a20-ee47-4388-9daa-e9476a8fb9ce" />

### Use o comando:
#### git config --list
## Agora crie um diretório
<img width="405" height="67" alt="image" src="https://github.com/user-attachments/assets/d79f1d07-814f-4f6b-bf49-5d06925b3b3a" />

### Usando o código:
#### mkdir nome_do_diretório
## Navegue para dentro desse diretório criado
<img width="541" height="139" alt="image" src="https://github.com/user-attachments/assets/7f03529d-1a8c-4dcc-bd6e-895ce0364767" />

### Usando o código: 
#### cd nome_do_diretório
## Inicializa um repositório
<img width="949" height="154" alt="image" src="https://github.com/user-attachments/assets/88848605-a8c5-4b4c-9a84-9a165327256a" />

### Usando o código:
#### git init repositorio
## Verifique se o repositório foi criado (procure pela pasta .git).
<img width="757" height="254" alt="image" src="https://github.com/user-attachments/assets/f03e2a6a-cbdd-48ca-ae82-53cb6cbb7855" />

### Usando o código:
#### cd repositorio para navegar para o repositorio
#### ls -la para listar os arquivos e verificar se a pasta .git está presente
## Crie um arquivo meu_primeiro_arquivo.txt.
<img width="792" height="62" alt="image" src="https://github.com/user-attachments/assets/97542242-cfa2-481a-a39a-323ef438279e" />


### Usando os códigos:
#### touch meu_primeiro_arquivo.txt

## Adicione o arquivo ao stage.
<img width="739" height="57" alt="image" src="https://github.com/user-attachments/assets/6ef6b511-6f5f-474e-a42f-0e4034f919ba" />


### Usando o código:
#### git add meu_primeiro_arquivo.txt

## Verifique o status do repositório.
<img width="783" height="279" alt="image" src="https://github.com/user-attachments/assets/589e4249-4091-4221-b452-7e62cd3f19f3" />


### Usando o código:
#### git status

## Faça um commit com mensagem descritiva
<img width="775" height="177" alt="image" src="https://github.com/user-attachments/assets/da4279d8-cf97-45da-b1ec-65c5934c0489" />


### Usando o código:
#### git commit -m "Sua mensagem aqui"

## Confira o status mais uma vez
<img width="798" height="90" alt="image" src="https://github.com/user-attachments/assets/f8361650-1767-41a2-9fcb-797c984a3221" />


### Usando o código
#### git status

## Visualize o histórico no diretório do repositório Git
<img width="824" height="195" alt="image" src="https://github.com/user-attachments/assets/f2271080-d93b-4520-87f6-f89d16419886" />

### Usando o código
#### git log
