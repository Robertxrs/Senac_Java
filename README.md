# Senac_Java_POO
Atividades do curso técnico de desenvolvimento de sistemas do Senac. Módulo 2(Programação Orientada a Objetos em Java). Os projetos enviados foram realizados na IDE Netbeans.

Atividade 1
Contexto:
-
1.Auditório Adequado para Eventos: O programa determina o auditório (Alfa ou Beta) mais adequado com base no número de convidados e calcula as cadeiras adicionais necessárias para o auditório Alfa.

2.Troca de Quartos entre Hóspedes: O programa atribui dois clientes a quartos A e B com base na idade e aplica um desconto de 40% se o cliente mais velho for idoso.

3.Controle de Hospedagem: O programa recebe o valor de uma diária, os nomes e idades dos hóspedes, calcula gratuidades para hóspedes com menos de 4 anos e meias hospedagens para hóspedes com mais de 80 anos, e mostra o valor total das hospedagens.

4.Cadastro e Pesquisa de Hóspedes: O programa permite cadastrar e pesquisar hóspedes, armazenando até 15 cadastros e oferecendo um menu com opções de cadastro, pesquisa e saída.

5.Tabela de Quartos Ocupados: O programa permite registrar os quartos ocupados em um hotel com 4 andares e 3 quartos por andar, exibindo uma tabela dos quartos ocupados.

Atividade 2 
-
Contexto:

A empresa de desenvolvimento está retornando ao projeto de desenvolvimento de um sistema para uma agência de viagens. O sistema deve permitir o registro de pacotes de viagens e dados de vendas. Cada pacote de viagem consiste em transporte e hospedagem, cada um com seu tipo e valor. Os valores dos pacotes incluem margem de lucro e taxas adicionais.

A venda inclui dados do cliente, forma de pagamento, data e o pacote de viagem, com a capacidade de converter o valor do pacote entre dólar e real.

Na classe principal, o programa permiti a interação com o usuário para criar um pacote de viagem e uma venda, mostrando informações relevantes, incluindo o valor total em dólar e real, com o usuário informando a cotação do dólar no dia. O uso de construtores nas classes. 

Atividade 3
Contexto:
-
Desenvolvi um sistema relacionado ao setor de Recursos Humanos e à folha de pagamento. Existem dois tipos de funcionários: assalariados e horistas. Ambos têm informações básicas, como nome, CPF, endereço, telefone e setor. Os assalariados têm um salário mensal fixo, enquanto os horistas têm horas trabalhadas e valor da hora.

As classe são capazes de mostrar os dados dos funcionários, calcular seus pagamentos de acordo com suas características e aplicar aumentos salariais. 

O programa principal permite ao usuário fornecer dados para até dez funcionários, perguntando o tipo (assalariado/horista) e armazenando os dados em uma única lista. Em seguida, ele exibe os dados e os pagamentos de cada funcionário. O programa também permite ao usuário aplicar um aumento geral para todos os funcionários e mostra novamente os pagamentos recalculados.

Atividade 4
Contexto:
-

No contexto apresentado, estamos desenvolvendo um módulo contábil para calcular impostos em vendas de produtos. Dois tipos de impostos, PIS e IPI, precisam ser representados. Cada imposto tem uma regra de cálculo específica, mas todos compartilham a necessidade de calcular o valor do imposto e mostrar sua descrição. O sistema deve é flexível para permitir a inclusão de novos tipos de impostos no futuro.

Para implementar esse sistema, planejei uma hierarquia de classes e interfaces que representam os impostos, além de uma classe "Pagamentos" para gerenciar a lista de impostos a serem pagos. No programa principal, permiti que o usuário forneça os dados da empresa, cadastre múltiplos impostos, independentemente do tipo, calcule o total para cada imposto e mostre a descrição.

O objetivo é criar uma estrutura que seja eficaz, flexível e reutilizável para lidar com os cálculos de diferentes tipos de impostos em um ambiente contábil.