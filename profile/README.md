# 🐂 BUBATAG

### Monitoramento inteligente de rebanhos por meio de IoT, software e dados.

**BUBATAG** é um projeto tecnológico focado no **manejo inteligente de búfalos e no bem-estar animal**, combinando **Internet das Coisas (IoT), sistemas embarcados, desenvolvimento de software e monitoramento de dados**.

Nosso objetivo é transformar os dados coletados dos animais em informações úteis que possam apoiar decisões mais rápidas, seguras e assertivas no manejo do rebanho.

---

## 🚀 Sobre o BUBATAG

O manejo de rebanhos de búfalos em grandes áreas de pastagem pode dificultar o monitoramento contínuo da localização e das condições de saúde de cada animal.

**O BUBATAG foi criado para enfrentar esse desafio.**

Nosso ecossistema combina um **dispositivo vestível inteligente**, **monitoramento de localização**, **sensores fisiológicos** e uma **plataforma web e mobile intuitiva** em uma solução integrada de monitoramento.

### O que o BUBATAG monitora

- 📍 Localização do animal
- ❤️ Frequência cardíaca
- 🌡️ Temperatura corporal
- 🚨 Alertas para animais fora das áreas monitoradas
- 📊 Informações e dados do rebanho
- 📱 Acesso web e mobile

> O BUBATAG foi desenvolvido como uma ferramenta de apoio à tomada de decisões, ajudando produtores a identificar possíveis alterações nas condições dos animais e agir mais rapidamente quando houver necessidade de atenção.

---

## ⚙️ Como funciona

```text
        🐂 ANIMAL
           │
           ▼
   ┌─────────────────┐
   │ COLEIRA INTELIGENTE │
   │                 │
   │ ESP32 + Sensores│
   └────────┬────────┘
            │
            ▼
   ┌─────────────────┐
   │ COLETA DE DADOS │
   │                 │
   │ Localização +   │
   │ Dados           │
   │ Fisiológicos    │
   └────────┬────────┘
            │
            ▼
   ┌─────────────────┐
   │ SISTEMA BUBATAG │
   │                 │
   │ API + Banco     │
   │ de Dados        │
   └────────┬────────┘
            │
       ┌────┴────┐
       ▼         ▼
   📱 MOBILE   🌐 WEB
       │         │
       └────┬────┘
            ▼
      🚨 ALERTAS E
       MONITORAMENTO
```

A coleira inteligente coleta informações do animal e se comunica com o ecossistema BUBATAG.

A plataforma processa e apresenta essas informações por meio de interfaces web e mobile, permitindo que os produtores monitorem seu rebanho remotamente.

Quando um animal sai de uma área monitorada, o sistema pode gerar um alerta, ajudando o produtor a agir com maior rapidez.

---

## 🧠 Tecnologias

O BUBATAG combina diferentes áreas de desenvolvimento de software e hardware:

| Área | Tecnologias |
|---|---|
| 🌐 Web | React, Next.js, TypeScript, JavaScript |
| 📱 Mobile | React Native |
| ⚙️ Backend | Node.js, Express |
| 🐂 IoT / Embarcados | ESP32, Sensores |
| 🗄️ Bancos de Dados | SQL / NoSQL |
| 🐳 Infraestrutura | Docker, Tecnologias em Nuvem |
| 🔧 Desenvolvimento | Git, GitHub, APIs REST |

A stack tecnológica continua evoluindo conforme o projeto avança.

---

## 🧩 Arquitetura do Projeto

O BUBATAG é organizado como um ecossistema composto por diferentes componentes interconectados:

```text
                    ┌──────────────────┐
                    │ COLEIRA INTELIGENTE │
                    │      ESP32       │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │ DADOS / REDE     │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │    API BUBATAG   │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │   BANCO DE DADOS │
                    └────────┬─────────┘
                             │
                    ┌────────┴─────────┐
                    ▼                  ▼
             ┌────────────┐     ┌────────────┐
             │    WEB     │     │   MOBILE   │
             │ DASHBOARD  │     │    APP     │
             └────────────┘     └────────────┘
```

---

## 📂 Repositórios

A organização do BUBATAG contém repositórios dedicados às diferentes partes do projeto.

| Repositório | Descrição |
|---|---|
| 🐂 **IoT / Embarcados** | Firmware, desenvolvimento com ESP32 e integração dos sensores. |
| ❤️ **Frequência Cardíaca** | Desenvolvimento e testes do monitoramento fisiológico. |
| 📱 **Mobile** | Aplicativo mobile para monitoramento do rebanho. |
| 🌐 **Web** | Plataforma web e dashboards. |
| 🔌 **API** | Serviços de backend e integração do sistema. |
| 🗄️ **Banco de Dados** | Modelagem e persistência dos dados. |
| 📚 **Documentação** | Documentação técnica e acadêmica. |

> Os nomes dos repositórios e os componentes podem evoluir ao longo do desenvolvimento.

---

## 🎯 Nossa Missão

Nossa missão é explorar como a tecnologia pode contribuir para um **melhor manejo do rebanho e para o bem-estar animal**.

Buscamos tornar o monitoramento do rebanho mais **acessível, intuitivo e orientado por dados**, ajudando os produtores a gastar menos tempo procurando informações e mais tempo tomando decisões assertivas.

---

## 🌱 Projeto Acadêmico

O BUBATAG está sendo desenvolvido como um **Projeto Integrador (PI)** por estudantes do curso de **Tecnologia em Desenvolvimento de Software Multiplataforma** da **Fatec Registro – Centro Paula Souza**, Brasil.

O projeto reúne conhecimentos de:

- Engenharia de Software
- Internet das Coisas
- Sistemas Embarcados
- Design UI/UX
- Bancos de Dados
- Redes de Computadores
- Desenvolvimento Mobile
- Desenvolvimento Web
- Metodologias Ágeis

---

## 👥 Equipe

Somos uma equipe multidisciplinar de estudantes de desenvolvimento de software, trabalhando em conjunto em diferentes áreas do ecossistema BUBATAG.

| Integrante | Área |
|---|---|
| **Matheus Ferrari** | Frontend / Backend |
| **Leonardo de Lima** | Frontend / Backend / Desenvolvimento de Software |
| **Vinícius de Souza** | Banco de Dados / Redes / Infraestrutura |
| **Arthur Fukunaga** | UX/UI Design / Frontend / Infraestrutura |

---

## 📈 Status do Projeto

🟡 **Em Desenvolvimento Ativo**

O BUBATAG está atualmente em desenvolvimento, com trabalhos em andamento envolvendo:

- Hardware IoT
- Integração de sensores
- Comunicação de dados
- Aplicações web e mobile
- Serviços de backend
- Experiência do usuário
- Testes do sistema

---

## 🤝 Colaboração

Estamos continuamente desenvolvendo e aprimorando o ecossistema BUBATAG.

Se você se interessa por **IoT, agricultura inteligente, bem-estar animal, desenvolvimento de software ou tecnologia aplicada ao agronegócio**, fique à vontade para explorar nossos repositórios.

---

# 🐃 Tecnologia trabalhando pelo seu rebanho.

**BUBATAG — Monitoramento inteligente para um manejo melhor.**
