# Manga

Aplicativo bancário completo desenvolvido em **React Native com Expo**.

<img src="https://user-images.githubusercontent.com/jean-cavalcante1/manga/logo.png" width="120" />

## Funcionalidades principais

- Login com segurança (autenticação Firebase)
- Dashboard com nome do usuário
- PIX: envio, recebimento, agendamento e QR Code
- Cartão virtual: ver dados, bloquear/desbloquear, gerar novo
- Histórico de transações e comprovantes em PDF
- Recarga de celular com operadoras brasileiras
- Boletos: pagamento e geração de depósito
- Suporte via chat
- Reconhecimento facial e verificação com RG (foto)
- Acessibilidade completa (modo escuro/claro, leitores de tela)
- Splash animado e efeitos sonoros no PIX

## Tecnologias

- Expo (React Native)
- Firebase (Auth, Firestore, Storage)
- Expo Router
- Context API
- Styled Components
- React Native Paper (UI)
- react-native-qrcode-svg / expo-camera

## Como rodar no seu celular (Android)

1. Instale o app **Expo Go** pela Play Store
2. Clone o repositório:

```bash
git clone https://github.com/jean-cavalcante1/manga.git
cd manga
npm install
npx expo start
