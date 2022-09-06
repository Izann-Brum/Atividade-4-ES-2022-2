# Atividade-4-ES-2022-2

**Descrição:**
1) Definir 2 requisitos funcionais de um sistema qualquer.
2) Descrever o Caso de Uso Expandido para os 2 requisitos.
3) Descrever User Storie para os 2 requisitos.
4) Fazer o protótipo da tela para cada um dos requisitos.
----------------------------------------------------------
Utilizaremos, como referência, um sistema para reservas de mesas de um restaurante qualquer.

1 - **Definição dos requisitos:**
	
Os 2 requisitos funcionais, desse sistema a serem descritos, são os seguintes: **Cadastrar Cliente e Efetuar Reserva**.	

----------------------------------------------------------
2 - **Descrição do caso de uso expandido dos requisitos:**

**Requisito 1:**

    • Nome: Cadastrar Cliente.
    • Número: 01.
    • Atores: Cliente, Funcionário.
    • Finalidade: Cadastrar um novo cliente.
    • Visão geral: Este caso de uso tem a finalidade de efetuar o cadastro de clientes que ainda não estejam cadastrados no sistema.
    • Tipo: Essencial

**Ações do atores:**
1. Cliente chega a recepção, informa o desejo de locar uma mesa.
2. Cliente informa seu nome, CPF, data de nascimento e e-mail.
3. O funcionário registra os dados do cliente.

**Respostas do sistema:**
1. Mostra tela de cadastro de clientes.
2. Sistema coloca tabela em modo de inserção.
3. Sistema grava informações.

**Tratamento de Exceções:**

1.1. Funcionário verifica que o cliente já possuí cadastrado.

1.2. Sistema disponibiliza tela de reservas.

2.1. Funcionário informa ao cliente que os dados podem estar desatualizados.

2.2. Sistema disponibiliza a tela de alteração.


**Requisito 2:**

    • Nome: Efeturar Reserva
    • Número: 02
    • Atores: Cliente, Funcionário
    • Finalidade: Efeturar reserva de uma mesa
    • Visão geral: Este caso de uso tem a finalidade de incluir a reserva de mesa mediante o cadastro do cliente
    • Tipo: Essencial

**Ações do atores:**
1. Cliente solicita a reserva de uma mesa.
2. Cliente informa o tipo de mesa em que deseja utilizar, e o número total de pessoas que se acomodarão.
3. Funcionário informa ao sistema todos os dados informados pelo cliente
4. Funcionário confirma a reserva com cliente.

**Respostas do sistema:**
1. Sistema disponibiliza a tela de Cadastro de Reservas.
2. Sistema coloca os campos em modo de inserção.
3. Sistema grava todos os dados informados
4. Sistema registra mesa como reservada.

**Tratamento de Exceções:**

1.1. Funcionário verifica que o cliente ainda não esta cadastrado, e efetua o cadastro.

1.2. Sistema disponibiliza tela de cadastro

2.1. Funcionário informa ao cliente que não existem quartos disponíveis.

2.2. Sistema encerra reserva.

----------------------------------------------------------

3 - **Descrição do User Storie para os requisitos:**

**Requisito 1:** <Cadastrar Cliente>
Como um < recepcionista > eu < preciso > de < permissões > especiais para <cadastrar> um novo usuário no sistema.

**Requisito 2:** <Efetuar Reserva>
Como um < cliente > eu < desejo > de forma breve < locar > uma mesa do tipo família para < usufruto > na data de hoje. 

----------------------------------------------------------

4 - **Protótipo das telas de cada requisito:**

 **Requisito:** Cadastrar Cliente

<img src="https://user-images.githubusercontent.com/61673451/188546833-18acea84-b5c2-4d09-8e6e-64d45c22a6f2.png" alt="drawing" width="600"/>

 **Requisito:** Efeturar Reserva

<img src="https://user-images.githubusercontent.com/61673451/188546888-eebfee53-566b-4c70-89e3-f3e1ca2db9a7.png" alt="drawing" width="600"/>
