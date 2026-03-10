
# React Native + Expo Profile App

Projeto criado para a disciplina **Programação para Dispositivos Móveis**.

## Estrutura
- components/Profile.tsx → Componente com foto, nome e mini bio
- index.tsx → Tela principal com título e o Profile

## Rodar o projeto

1. Instale dependências
npm install

2. Inicie o Expo
npx expo start

3. Escaneie o QR Code no aplicativo **Expo Go** no celular.

## Publicar OTA Update

1. Instalar EAS CLI
npm install -g eas-cli

2. Login
eas login

3. Configurar
eas init

4. Enviar update
eas update --auto

Após executar o comando acima, o Expo irá gerar um **QR Code OTA** que pode ser compartilhado como link para entrega da atividade.
