# Perfil Github

![React Native](https://img.shields.io/badge/React%20Native-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Aplicativo mobile desenvolvido em React Native para exibir um perfil do Github de forma estilizada e interativa.

[Sobre o Projeto](#sobre-o-projeto) • [Funcionalidades](#funcionalidades) • [Tecnologias](#tecnologias) • [Instalação](#instalação) • [Uso](#uso) • [Estrutura](#estrutura-do-projeto)

---

## Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Tecnologias](#tecnologias)
- [Instalação](#instalação)
- [Uso](#uso)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Conceitos Aplicados](#conceitos-aplicados)
- [Licença](#licença)

---

## Sobre o Projeto

Este projeto foi desenvolvido como parte do curso de **Introdução ao React Native** da **DIO (Digital Innovation One)**. O aplicativo apresenta uma interface moderna de perfil de usuário com informações personalizadas, navegação fluida entre telas e integração com links externos.

### Principais Características

- 📱 **Interface Mobile Nativa** - Experiência otimizada para dispositivos móveis
- 🎨 **Design Responsivo** - Layout adaptável usando Flexbox
- 🔗 **Linking API** - Integração com URLs externas
- 🧭 **Navegação Intuitiva** - Transições suaves entre telas
- ⚡ **Performance Otimizada** - Desenvolvido com Expo para melhor desempenho

---

## Funcionalidades

### Telas Principais

#### Tela de Boas-Vindas

- Apresentação inicial do aplicativo
- Design atrativo e amigável
- Botão de navegação para o perfil

#### Tela de Perfil

- Exibição de informações do usuário
- Imagem de perfil
- Links para redes sociais e repositórios
- Botões interativos personalizados

### Recursos Implementados

- ✅ Navegação entre múltiplas telas
- ✅ Layout responsivo com Flexbox
- ✅ Componentes personalizados reutilizáveis
- ✅ Integração com Linking API para abertura de URLs
- ✅ SafeAreaView para compatibilidade com diferentes dispositivos
- ✅ StatusBar configurável

---

## Tecnologias

### Mobile

| Tecnologia       | Versão | Descrição                                    |
| ---------------- | ------ | -------------------------------------------- |
| React Native     | -      | Framework para desenvolvimento mobile        |
| Expo             | -      | Plataforma para desenvolvimento React Native |
| React Navigation | -      | Biblioteca de navegação                      |
| JavaScript       | ES6+   | Linguagem de programação                     |

### Componentes e APIs

- **View & Text** - Componentes básicos de UI
- **StyleSheet** - Estilização de componentes
- **SafeAreaView** - Área segura para diferentes dispositivos
- **StatusBar** - Controle da barra de status
- **Image** - Exibição de imagens
- **Linking API** - Abertura de URLs externas

---

## Instalação

### Pré-requisitos

- Node.js - [Download](https://nodejs.org/)
- Expo CLI - Instalado globalmente
- Expo Go - Aplicativo para testar em dispositivo físico

### Instalação Local

#### 1. Clone o repositório

```bash
git clone https://github.com/nevesmarcos42/Perfil-Github.git
cd Perfil-Github
```

#### 2. Instale as dependências

```bash
npm install
```

#### 3. Inicie o projeto

```bash
npm start
```

Pronto! Use o Expo Go para escanear o QR Code e visualizar o app no seu dispositivo.

---

## Uso

### Primeiro Acesso

1. **Abra o aplicativo** no Expo Go
2. **Tela de Boas-Vindas** será exibida
3. **Navegue** para a tela de perfil usando o botão
4. **Explore** as informações e links disponíveis

### Comandos Disponíveis

```bash
# Iniciar o projeto
npm start

# Rodar no Android
npm run android

# Rodar no iOS
npm run ios

# Rodar na Web
npm run web
```

---

## Estrutura do Projeto

```
Perfil-Github/
├── App.js              # Componente principal
├── app.json            # Configurações do Expo
├── babel.config.js     # Configurações do Babel
├── package.json        # Dependências do projeto
├── assets/             # Imagens e recursos estáticos
└── src/
    ├── pages/
    │   ├── Welcome/    # Tela de boas-vindas
    │   │   └── index.js
    │   └── SignIn/     # Tela de perfil
    │       └── index.js
    └── routes/         # Configuração de navegação
        └── index.js
```

---

## Conceitos Aplicados

Durante o desenvolvimento deste projeto, foram explorados e aplicados os seguintes conceitos do React Native:

### Componentes Fundamentais

- **View** - Container básico para layout
- **Text** - Exibição de texto
- **Image** - Renderização de imagens

### Estilização

- **StyleSheet** - Criação de estilos otimizados
- **Flexbox** - Sistema de layout responsivo
- **Cores e Tipografia** - Customização visual

### Navegação

- **Stack Navigator** - Navegação em pilha
- **Transições de Tela** - Animações suaves

### APIs e Recursos

- **SafeAreaView** - Compatibilidade com notch
- **StatusBar** - Controle da barra superior
- **Linking API** - Abertura de URLs externas

### Boas Práticas

- Componentização e reutilização de código
- Organização de arquivos e pastas
- Separação de responsabilidades

---

## Licença

Este projeto foi desenvolvido para fins educacionais como parte do curso da DIO.

---

**Desenvolvido como projeto educacional React Native**

**Versão:** 1.0.0

**Última Atualização:** Novembro 2025
