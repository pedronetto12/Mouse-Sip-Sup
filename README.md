# 🖱️ Mouse Inclusivo Sip-and-Puff

> Um projeto de tecnologia assistiva de **hardware e software abertos**, criado para promover **acessibilidade digital** com baixo custo.

## 💡 Sobre o Projeto

Este repositório apresenta o desenvolvimento de um **mouse controlado por sopro e sucção (Sip-and-Puff)**, pensado para pessoas com comprometimento motor severo e controle de cabeça preservado. O dispositivo permite o controle do cursor e cliques por meio de ações com a boca — como soprar ou sugar — utilizando componentes acessíveis e de baixo custo.

O projeto foi desenvolvido no ambiente universitário, com o objetivo de ser **gratuito, aberto e replicável**, fortalecendo o acesso democrático à tecnologia assistiva no Brasil.

## 🔧 Como Funciona

- **Joystick** detecta o movimento da cabeça do usuário.
- **Sensor de pressão** converte o sopro/sucção em sinais elétricos.
- **Arduino Pro Micro** interpreta os sinais e simula um mouse via USB.

| Ação com a boca    | Função no mouse   |
|--------------------|-------------------|
| Sopro forte        | Clique esquerdo   |
| Sucção forte       | Clique direito    |
| Sopro/sucção leve  | Rolagem de página |

## 📦 Componentes Principais

- Arduino Pro Micro (ATmega32U4)
- Sensor de pressão MPS20N0040D-S
- Módulo joystick KY-023
- Impressão 3D em PLA para a estrutura física

![Mouse](https://github.com/pedronetto12/Mouse-Sip-Sup/blob/main/mouse%20sip%26suff.jpeg)

## 📊 Desempenho

| Parâmetro         | Sip-and-Puff | Mouse Convencional |
|------------------|---------------|----------------------|
| Frequência (Hz)  | 96            | 220                  |
| Velocidade (m/s) | 0.26          | 0.51                 |
| Precisão (%)     | 98.1          | 98.2                 |
| Custo estimado   | R$ 250        | ~R$ 2.000            |

Apesar da performance inferior em velocidade e polling rate, o mouse desenvolvido apresenta excelente **precisão funcional**, o que o torna uma alternativa viável para uso real.

## 📌 Objetivos

- 🧠 Promover **autonomia** e **inclusão digital**
- 🔓 Ser totalmente **open-source**
- 🤝 Incentivar a **inovação colaborativa**

## 📄 Publicação

Este projeto foi apresentado no **Congresso Brasileiro de Tecnologia Assistiva (CBTA)** como artigo técnico:

> **Grangeiro, Pedro Netto Gandolfi et al.** *Mouse inclusivo de hardware e software aberto controlado por sopro e sucção.* CBTA, 2023.

## 🤝 Agradecimentos

Agradecimentos à **UDESC** pelo suporte institucional e aos professores e colegas envolvidos.

## 📥 Contribua!

Quer contribuir? Tem ideias para melhorias? Fique à vontade para abrir uma issue ou enviar um pull request! Vamos juntos tornar a tecnologia mais inclusiva 💙
