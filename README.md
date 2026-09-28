# Minha Cola Eleitoral 2026 — Android

Projeto Android Studio simples, offline e sem login/servidor.

## Como gerar o APK
1. Abra esta pasta no Android Studio.
2. Aguarde o Gradle sincronizar e instale o SDK solicitado, se o Android Studio pedir.
3. Use **Build > Build APK(s)**.
4. O APK de debug será gerado em `app/build/outputs/apk/debug/app-debug.apk`.

## Conteúdo
- Interface web local em `app/src/main/assets/index.html`
- Base de candidatos em `candidatos.json`
- Fotos oficiais fornecidas pelo usuário em `assets/fotos/`
- WebView offline usando `WebViewAssetLoader`

## Observação
Os dados são uma cópia da base enviada para esta conversa e não são atualizados automaticamente.
