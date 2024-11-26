# Delivery App

Esse é um projeto [Expo](https://expo.dev) feito com [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Execução do Projeto

### 1. Instale as dependências
Abra um terminal na pasta raiz do projeto e execute o comando:

```bash
npm install
```

### 2. Configure a API

1. Localize o IPv4 de sua máquina.
2. Dentro da pasta **src/components**, procure pelas pastas **list**, **restaurants** e **trending** e, nos arquivos **index.tsx** de cada uma, substitua o ip dentro da variável **localIpv4** pelo IPv4 da sua máquina.

### 3. Rode a API localmente

Abra um outro terminal na pasta raiz do projeto e execute o comando:

```bash
 npx json-server db.json
```

### 4. Rode o aplicativo
No mesmo terminal em que instalou as dependências, execute o comando:

```bash
 npx expo start
```

Você vai encontrar uma lista de opções para rodar o projeto:

- [Build de Desenvolvimento](https://docs.expo.dev/develop/development-builds/introduction/).
- [Emulador Android](https://docs.expo.dev/workflow/android-studio-emulator/).
- [Simulador iOS](https://docs.expo.dev/workflow/ios-simulator/).
- [Expo Go](https://expo.dev/go), um aplicativo criado para visualizar projetos Expo, disponível em Android e iOS.

Escolha a de sua preferência e siga as instruções.
