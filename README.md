# 🖱️ Mouse Inclusivo Sip-and-Puff

> Um projeto de tecnologia assistiva de **hardware e software abertos**, criado para promover **acessibilidade digital** com baixo custo.

## 💡 Sobre o Projeto

Este repositório apresenta o desenvolvimento de um **mouse controlado por sopro e sucção (Sip-and-Puff)**, pensado para pessoas com comprometimento motor severo e controle de cabeça preservado. O dispositivo permite o controle do cursor e cliques por meio de ações com a boca — como soprar ou sugar — utilizando componentes acessíveis e de baixo custo.

O projeto foi desenvolvido no ambiente universitário, com o objetivo de ser **gratuito, aberto e replicável**, fortalecendo o acesso democrático à tecnologia assistiva no Brasil.

![Mouse Inclusivo Sip-and-Puff](https://github.com/pedronetto12/Mouse-Sip-Sup/blob/main/mouse.png)

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

![Fluxograma](https://github.com/pedronetto12/Mouse-Sip-Sup/blob/main/fluxograma%20projeto.png)

## 📌 Objetivos

- 🧠 Promover **autonomia** e **inclusão digital**
- 🔓 Ser totalmente **open-source**
- 🤝 Incentivar a **inovação colaborativa**

## 📄 Publicação

Este projeto foi apresentado no **Congresso Brasileiro de Tecnologia Assistiva (CBTA)** como artigo técnico:

> **Grangeiro, Pedro Netto Gandolfi et al.** *Mouse inclusivo de hardware e software aberto controlado por sopro e sucção.* CBTA, 2023.

## 🛠️ Atualização no Design do Bocal

Realizamos uma **melhoria significativa no bocal** do dispositivo. Agora, o mouse conta com:

- 💨 **Ponta substituível**, garantindo mais higiene e praticidade no uso;
- 🦠 **Filtro antibactericida**, promovendo segurança em ambientes clínicos e domiciliares;
- 🔄 Projeto mais modular e de fácil substituição.

![Mouse Atualizado](https://github.com/pedronetto12/Mouse-Sip-Sup/blob/main/mouse%20sip%26suff.jpeg)

Essa atualização reforça o compromisso do projeto com a usabilidade, segurança e conforto das pessoas com deficiência que irão utilizá-lo.

## 🤝 Agradecimentos

Agradecimentos à **UDESC** pelo suporte institucional e aos professores e colegas envolvidos.

## 📥 Contribua!

Quer contribuir? Tem ideias para melhorias? Fique à vontade para abrir uma issue ou enviar um pull request! Vamos juntos tornar a tecnologia mais inclusiva 💙
