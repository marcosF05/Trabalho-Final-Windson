# CineVault — Trabalho Final

Este pacote contém os dois clientes do app CineVault, conforme exigido pela atividade:

## 📁 cinevault-android/
Cliente **Android Nativo** desenvolvido em **Kotlin**, com arquitetura MVVM,
Firebase (Auth + Firestore), consumo da API TMDB via Retrofit, e biometria
via BiometricPrompt.

## 📁 cinevault-rn/
Cliente **Cross-platform** desenvolvido em **React Native**, com a mesma
base de funcionalidades, consumindo o mesmo backend Firebase, usando
react-native-biometrics para autenticação biométrica.

## ⚠️ Antes de rodar
Ambos os projetos precisam que você:
1. Crie um projeto no Firebase Console (https://console.firebase.google.com)
2. Ative Authentication (e-mail/senha) e Firestore Database
3. Baixe o `google-services.json` para cada app (ou use o mesmo projeto para os dois)
4. Crie uma conta gratuita no TMDB (https://www.themoviedb.org) e gere uma API key
5. Substitua as chaves de exemplo nos arquivos indicados em cada README

Veja o README.md dentro de cada pasta para instruções detalhadas de instalação.

## Requisitos da atividade atendidos
| Requisito | Onde está |
|---|---|
| CRUD completo | repository/ (Android) e services/firebase.ts (RN) |
| Backend Firebase | Firestore + Authentication em ambos |
| Serviço REST externo | TMDB API em ambos |
| Biometria | BiometricPrompt (Android) / react-native-biometrics (RN) |
| Cliente Android Nativo | cinevault-android/ (Kotlin) |
| Cliente Cross-platform | cinevault-rn/ (React Native) |
| Acessibilidade | contentDescription / accessibilityLabel em todas as imagens e botões |
| Dois idiomas | strings.xml / strings-en.xml (Android) e i18n/locales (RN) |
