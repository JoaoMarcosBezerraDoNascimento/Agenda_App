# Agenda App

## Descrição

Este é um aplicativo simples de agenda desenvolvido em Kotlin para dispositivos Android. Ele permite que os usuários adicionem, visualizem e recebam notificações para atividades agendadas.

## Funcionalidades

- Adicionar atividades com nome, data, hora e frequência.
- Visualizar atividades ordenadas por data e hora.
- Receber notificações diárias com as atividades do dia.

## Tecnologias Utilizadas

- Linguagem de programação: Kotlin
- SDK: Android
- Bibliotecas: Android Jetpack (SharedPreferences, NotificationManager, etc.)
- APIs: Android AlarmManager, JobScheduler

## Como usar

1. **Adicionar Atividade**: Clique no botão "Adicionar" para inserir uma nova atividade com nome, data, hora e frequência.
2. **Visualizar Atividades**: As atividades serão exibidas em uma lista ordenada por data e hora.
3. **Editar ou Excluir Atividades**: Clique em uma atividade na lista para editar ou excluí-la.
4. **Notificações**: Receba notificações diárias com as atividades programadas para o dia.

## Configurações de Notificação

O aplicativo cria um canal de notificação chamado "agenda_notification_channel" para gerenciar as notificações. Ele também permite que as atividades sejam programadas para notificações diárias, semanais, mensais ou anuais, conforme a preferência do usuário.

## Contribuição

Se você encontrar algum problema ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.
