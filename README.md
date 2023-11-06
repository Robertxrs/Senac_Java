# Senac_Java_POO
Atividades do curso técnico de desenvolvimento de sistemas do Senac. Módulo 2(Programação Orientada a Objetos em Java). Os projetos enviados foram realizados na IDE Netbeans.

Atividade 1: 
Contexto

Problema 1 - Auditório Adequado para Eventos:
O programa recebe o número de convidados para um evento e determina qual auditório (Alfa ou Beta) é o mais adequado. Se o número for inválido, exibe "Número de convidados inválido". Para o auditório Alfa, calcula quantas cadeiras adicionais são necessárias.

Problema 2 - Troca de Quartos entre Hóspedes:
O programa recebe o nome e idade de dois clientes, atribui-os aos quartos A e B e decide quem fica em qual quarto com base na idade. Se o cliente mais velho for idoso (60 anos ou mais), ele recebe um desconto de 40%.

Problema 3 - Controle de Hospedagem:
O programa recebe o valor padrão de uma diária e os nomes e idades dos hóspedes. Hóspedes com menos de 4 anos não pagam (gratuidade), e hóspedes com mais de 80 anos pagam metade (meia). O programa mostra a quantidade de gratuidades, meias hospedagens e o valor total das hospedagens.

Problema 4 - Cadastro e Pesquisa de Hóspedes:
O programa permite ao usuário cadastrar e pesquisar hóspedes. Ele oferece um menu com opções para cadastrar, pesquisar ou sair. O programa pode armazenar até 15 cadastros e permite pesquisar por nome, exibindo o índice onde o hóspede foi cadastrado.

Problema 5 - Tabela de Quartos Ocupados:
O programa permite registrar os quartos ocupados em um hotel com 4 andares e 3 quartos por andar. O usuário pode informar os quartos ocupados e, em seguida, o programa exibe uma tabela mostrando os quartos ocupados marcados com "X".

Atividade 2 
Contexto:

A empresa de desenvolvimento está retornando ao projeto de desenvolvimento de um sistema para uma agência de viagens. O sistema deve permitir o registro de pacotes de viagens e dados de vendas. Cada pacote de viagem consiste em transporte e hospedagem, cada um com seu tipo e valor. Os valores dos pacotes incluem margem de lucro e taxas adicionais.

A venda inclui dados do cliente, forma de pagamento, data e o pacote de viagem, com a capacidade de converter o valor do pacote entre dólar e real.

Na classe principal, o programa permiti a interação com o usuário para criar um pacote de viagem e uma venda, mostrando informações relevantes, incluindo o valor total em dólar e real, com o usuário informando a cotação do dólar no dia. O uso de construtores nas classes. 

Atividade 3
Contexto:
Desenvolvi um sistema relacionado ao setor de Recursos Humanos e à folha de pagamento. Existem dois tipos de funcionários: assalariados e horistas. Ambos têm informações básicas, como nome, CPF, endereço, telefone e setor. Os assalariados têm um salário mensal fixo, enquanto os horistas têm horas trabalhadas e valor da hora.

As classe são capazes de mostrar os dados dos funcionários, calcular seus pagamentos de acordo com suas características e aplicar aumentos salariais. 

O programa principal permite ao usuário fornecer dados para até dez funcionários, perguntando o tipo (assalariado/horista) e armazenando os dados em uma única lista. Em seguida, ele exibe os dados e os pagamentos de cada funcionário. O programa também permite ao usuário aplicar um aumento geral para todos os funcionários e mostra novamente os pagamentos recalculados.

Atividade 4
Contexto:

No contexto apresentado, estamos desenvolvendo um módulo contábil para calcular impostos em vendas de produtos. Dois tipos de impostos, PIS e IPI, precisam ser representados. Cada imposto tem uma regra de cálculo específica, mas todos compartilham a necessidade de calcular o valor do imposto e mostrar sua descrição. O sistema deve é flexível para permitir a inclusão de novos tipos de impostos no futuro.

Para implementar esse sistema, planejei uma hierarquia de classes e interfaces que representam os impostos, além de uma classe "Pagamentos" para gerenciar a lista de impostos a serem pagos. No programa principal, permiti que o usuário forneça os dados da empresa, cadastre múltiplos impostos, independentemente do tipo, calcule o total para cada imposto e mostre a descrição.

O objetivo é criar uma estrutura que seja eficaz, flexível e reutilizável para lidar com os cálculos de diferentes tipos de impostos em um ambiente contábil.