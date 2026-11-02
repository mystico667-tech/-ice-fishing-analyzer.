# Ice Fishing Analyzer — protótipo 0.1

Este é um projeto Android nativo (Kotlin) para abrir no Android Studio.

## O que já funciona
- Interface para registrar manualmente um resultado por rodada.
- Histórico local em memória durante a execução.
- Contagem e percentual de cada categoria.
- Destaque da categoria mais frequente, explicitamente como estatística histórica e não como previsão.

## O que ainda não está implementado
- Captura contínua da transmissão/tela do jogo.
- Reconhecimento automático dos pontos coloridos.
- Janela flutuante sobre o jogo.
- Persistência do histórico após fechar o aplicativo.
- Validação do significado exato de cada ponto/multiplicador.

A captura enviada permite desenhar a interface, mas não comprova que cada cor dos pontos corresponde a uma categoria específica. Não existe acesso à transmissão pelo ID da conta 1Win; qualquer leitura futura deve usar a captura de tela autorizada pelo Android e respeitar as permissões do sistema.

## Como gerar o APK
1. Abra esta pasta no Android Studio (versão recente).
2. Aguarde a sincronização do Gradle.
3. Use **Build > Build APK(s)**.
4. O APK de depuração ficará em `app/build/outputs/apk/debug/app-debug.apk`.

Este projeto ainda não é um APK compilado. O ambiente de criação desta entrega não tem Android SDK/Gradle instalados para compilar e testar o binário.
