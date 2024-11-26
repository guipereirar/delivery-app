# Delivery App

Esse é um projeto [Expo](https://expo.dev) feito com [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Execução do Projeto

### 1. Instale as dependências

```bash
npm install
```

### 2. Rode o aplicativo

```bash
 npx expo start
```

No terminal, você vai achar uma lista de opções para rodar o projeto:

- [Build de Desenvolvimento](https://docs.expo.dev/develop/development-builds/introduction/).
- [Emulador Android](https://docs.expo.dev/workflow/android-studio-emulator/).
- [Simulador iOS](https://docs.expo.dev/workflow/ios-simulator/).
- [Expo Go](https://expo.dev/go), um aplicativo criado para visualizar projetos Expo, disponível em Android e iOS.

Escolha o de sua preferência e siga as instruções.

### 3. Configure a API

1. Localize o IPv4 de sua máquina.
2. Dentro da pasta **src/components**, procure pelas pastas **list**, **restaurants** e **trending** e, nos arquivos **index.tsx** de cada uma, substitua o ip na vatiável **localIpv4** pelo IPv4 que localizou anteriomente.

### 4. Rode a API localmente

Abra um terminal diferente na pasta raiz do projeto e execute o comando:

```bash
 npx json-server db.json
```
