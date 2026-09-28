# Cola Eleitoral 2026 — compilação automática

Este projeto já contém os dados e fotos usados na versão Android offline.

## Gerar o APK pelo GitHub, usando apenas o celular

1. Crie/abra um repositório no GitHub.
2. Envie **o conteúdo desta pasta** para a raiz do repositório (não envie o ZIP como um único arquivo).
3. Faça o commit na branch `main`.
4. Abra a aba **Actions**.
5. O workflow **Gerar APK** será executado automaticamente após o push.
6. Quando terminar, abra a execução concluída.
7. Na seção **Artifacts**, toque em **ColaEleitoral2026-APK** para baixar o APK.

Também é possível iniciar manualmente em **Actions → Gerar APK → Run workflow**.

O APK gerado é uma versão `debug`, adequada para instalar e testar no aparelho. Para distribuição pública, seria necessário criar uma assinatura de release.
