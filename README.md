## 15/10
## Diagrama de Atividade 
O processo começa quando um estudante acessa o aplicativo, escolhe um lanche e informa o local onde deseja recebê-lo.
O sistema verifica se o lanche está disponível na cantina.
Caso o produto esteja indisponível, o aplicativo informa a situação e permite que o estudante escolha outro lanche ou cancele o pedido. Caso o estudante escolha outro produto, uma nova verificação de disponibilidade deverá ser realizada.
Quando o produto está disponível, o sistema verifica se existe algum robô livre e com bateria suficiente para realizar a entrega.
Se não houver robôs disponíveis, o estudante é informado e o processo é encerrado.
Caso exista um robô disponível, o aplicativo solicita o pagamento do pedido.
Se o pagamento não for aprovado, o pedido é cancelado. Caso contrário, o sistema confirma o pedido e reserva o robô responsável pela entrega.
A partir desse momento, duas atividades acontecem simultaneamente:
- A cantina prepara o lanche e embala o pedido.
- O sistema calcula a melhor rota até o destino e envia as informações de navegação ao robô.
Após a conclusão das duas atividades, o robô coleta o pedido na cantina e inicia seu deslocamento pelo campus.
Durante o percurso, o robô verifica continuamente se existem obstáculos em seu caminho. Sempre que um obstáculo for identificado, o sistema deverá recalcular a rota para permitir que o robô continue a entrega.
Quando o robô chega ao destino, o sistema envia um código de retirada ao estudante.
O estudante informa o código no painel do robô, e o sistema verifica se ele está correto.
Se o código estiver correto, o compartimento é aberto, o estudante retira seu pedido e o sistema registra a entrega como concluída.
Caso o código esteja incorreto, o compartimento permanece bloqueado e uma notificação é encaminhada à equipe de suporte.
Por fim, independentemente do resultado da tentativa de retirada, o robô retorna à sua base, encerrando o processo.


## 08/10
## Diagrama de atividades Maquina de Estado
- U.M.L Linguagem Unificada  de Modelagem
- CASE
- Ação não pode ter duas saída dela - mas chegar pode 
- Sempre tem que chegar no final 
## Programa Astah UML

<img width="952" height="357" alt="{8D3D95B4-0D09-4858-BA01-D66E51262B1F}" src="https://github.com/user-attachments/assets/cf7e427d-13b4-4609-9d25-6930f1439e8e" />
<img width="856" height="350" alt="{59A56B97-970D-45E0-A007-000AD2B20F73}" src="https://github.com/user-attachments/assets/cf5d0a8c-674f-4a8c-855f-9f39c77ecf2a" />
<img width="893" height="391" alt="{C83C1832-0F04-4B33-BD19-FCB6337321FC}" src="https://github.com/user-attachments/assets/c41e5392-37fa-48de-b0b6-58bf6ea208af" />
<img width="975" height="423" alt="{6B3069BE-BBAA-48DC-A40F-252D0EBEABC7}" src="https://github.com/user-attachments/assets/d5c49b63-3a88-47e2-acf3-3cde926ad982" />
<img width="957" height="427" alt="{CDE9F916-6DC2-4D53-930C-80DD6AE4803C}" src="https://github.com/user-attachments/assets/68b46222-8d5c-44f7-b77f-84b8761e7fdb" />
<img width="918" height="375" alt="{FE9B09D8-CF3F-4A72-BD5D-EA01CA02CC12}" src="https://github.com/user-attachments/assets/70a88d67-4402-4700-99ba-d7d9f934ab46" />
<img width="979" height="431" alt="{10CBC81D-865F-43D9-8B8B-27DC3118AEB9}" src="https://github.com/user-attachments/assets/2c6222ac-8ebc-4387-902c-ad2dd824b8ef" />
<img width="919" height="386" alt="{D4D3B57B-17C6-4BB4-9482-15E2F154A94D}" src="https://github.com/user-attachments/assets/794abd4f-7dbd-453d-90ba-085fdf6c95b5" />









## Trabalho avião por ciclos Finqtec
- 2 a 3 min de comunicação
- 7 a 8 min de desenvolvimento

- avião mais de manobra!
- avião ponta dobrada
- avião tem que girar 
- assas retas curvada para cima nas laterais, com corte na traseira da asa com dobra para cima!
- meio Malhado

<img width="1126" height="1227" alt="WhatsApp Image 2026-09-03 at 19 56 08" src="https://github.com/user-attachments/assets/275a3507-b091-4aca-a9f4-f5ebcf690474" />



**Desenvolvimento Ágil**
Todo modelo ágil tem que ter um nível de flexibilidade!
Toda metodologia ágil ela fraciona a entrega tendo uma entrega mais rápido, assim segue o gráfico o custo é maior inicialmente.
Tendo comunicação constante no processo com o cliente

<img width="939" height="382" alt="{200FDE8E-309B-49A5-89BC-3F3655A35714}" src="https://github.com/user-attachments/assets/38337f9b-009c-4025-8a51-019c58cd20f9" />




**O que é engenharia, dado um exemplo de construir uma casa**
*3 Quartos*
*Suite*
*Sala/ Cozinha*
*120 m*
*Piso*
*Tipo de Tijolo*
*Energia*
**Ex:**
<img width="916" height="715" alt="Captura de tela 2026-08-13 192442" src="https://github.com/user-attachments/assets/e851bcf7-1662-4cd3-a31f-98ced673e079" />



 **Engenharia ela e o processo de construção de alguma coisa**
  - Objetivo entregar algo de qualidade 
    - Teste uma ferramenta de qualidade

 **Software**
   - Conjunto de instruções
   - Dados
   - Documentação

 **Modelo Interativo**
  - Conjunto
      - Planejamento
          - Produção
              - construção
                  - Entrega 

Obs: Nem sempre um desenvolvimento/modelo vai seguir de forma linear; lembrando que pode ser conversado e haver mudanças um exemplo digamos construir mais um quarto. Em um programa fazer algumas mudanças

**Modelo Cascata**
O mais classico segue de forma linear trabalhando muito bem a comunicação.
- ponto negativo que pode haver demora para entregar o sistema por ter que esperar todas etapas.
- Raramente seguem o fluxo sequencial que o modelo propõe (mudanças podem provocar confusão) 

**Modelo V**
<img width="364" height="431" alt="image" src="https://github.com/user-attachments/assets/3d46da7d-4e32-44af-8240-f0c7f5acffb6" />

O Modelo V propõe uma troca maior com devidos testes trazendo uma garantia de qualidade
- Ainda existe uma demora no processo de entrega

**Modelo Incremental**
<img width="733" height="374" alt="image" src="https://github.com/user-attachments/assets/421e95ce-c94f-4173-acbc-c029a2cfdbe7" />

**Modelo Prototipação**
- Projeto rapido que e avaliado tendo um retorno(feedback) assim podendo aprimorar requisitos, possibilitando melhor compreensão das necessidades.

<img width="430" height="358" alt="image" src="https://github.com/user-attachments/assets/f1055574-1357-4065-ad34-404ead8a72f1" />

Pontos negativos os interessados enxergam o que parece ser uma versão operacional mas é só um protótipo, não se considerando qualidade global e nem sua manutenção em longo prazo.  


**Modelo Espiral**
É um gerador de modelos de processos dirigidos a riscos e é utilizado para guiar de melhor forma tendo multiplos envolvidos.
<img width="435" height="340" alt="image" src="https://github.com/user-attachments/assets/74b3ddb0-7e0e-45cd-bd44-9a53e0b2acb8" />

Ponto negativo: Pode ser difícil de convencer o cliente podendo haver mudanças de valores em cada etapa. Exige especialização na avaliação de riscos.

